---
layout: default
title: helper-scripts
nav_order: 327
parent: binary-ppc64el
grand_parent: bullseye-testers main
---

**Package:** helper-scripts

**Version:** 3:18.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  247

**Recommends:**  

**Conficts:**  

**Replaces:**  anon-shared-helper-scripts, anon-ws-leaktest, curl-scripts, python-guimessages, python3-guimessages

**Provides:**  

**Homepage:**  [https://github.com/Whonix/helper-scripts](https://github.com/Whonix/helper-scripts)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/h/helper-scripts/helper-scripts_18.7-1_all.deb

**Size:**  247

**Sha256:**  110c0c2791bda13bb51fe3f4b503f73c4036e7b64f571f5ccc173afe6ff730fb

**Sha1:**  92fee5f8ba1170c5c26eb82037d3c849c39ceefc

**Md5sum:**  0f9410e9b1078c5da8b8f16c073cbb47

**Description:** Helper scripts useful for Linux Distributions
 Contains a script for curl progress bar in terminal. Includes another script
 to convert curl exit codes to curl status messages. Implemented in bash.
 Common code that can be used by other scripts.
 .
 Library that can be used by other (anonymity related) packages that want to
 programmatically get information about states of Tor. Common code, that is
 often required. Includes bash and Python helper scripts.
 .
 Leak Test for Anonymity Distribution Workstations
 Integrated leak test.
 Needs to be manually run.
 See: https://www.whonix.org/wiki/Dev/Leak_Tests
 .
 Translatable GUI Messages
 Generic modules guimessage.py and translations.py.
 Called with two parameters: .yaml file path and yaml section. Return
 translations according to distribution local language (Python 'locale').
 .
 Provides the ld-system-preload-disable wrapper to disable /etc/ld.so.preload
 per application via bubblewrap. Useful if hardened_malloc is being globally
 preloaded and needs to be disabled for some applications.


