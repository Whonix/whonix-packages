---
layout: default
title: tb-starter
nav_order: 131
parent: binary-s390x
grand_parent: bullseye-developers main
---

**Package:** tb-starter

**Version:** 3:14.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  132

**Recommends:**  tb-updater, tb-default-browser, open-link-confirmation, icon-pack-dist

**Conficts:**  

**Replaces:**  

**Provides:**  torbrowser-launcher

**Homepage:**  [https://github.com/Whonix/tb-starter](https://github.com/Whonix/tb-starter)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tb-starter/tb-starter_14.8-1_all.deb

**Size:**  132

**Sha256:**  93367f1e4e8bffb3fad1d0f54d5641fa64695712a54dc57b780b77c025f534c2

**Sha1:**  ea43111b63dc1ea30640d4ec12476bcb909ba908

**Md5sum:**  9b57391c01489ee9759ec2ee59926560

**Description:** Tor Browser Starter (by Whonix developers)
 Both, a starter for Tor Browser.
 Provides security hardening, integration with Debian, Whonix and Qubes.
 .
 Starter.
 .
  - Tor Browser Starter start menu entry and `/usr/bin/torbrowser`
 starter. Starts `/home/user/.tb/tor-browser/start-tor-browser`.
 .
 When config option tb_hardening=true is set or when using
 command line option --hardening, firejail will be used.
 .
 Uses open-link-confirmation if available.
 .
 Prompts to install the browser if not yet installed.
 .
 Changes directory into browser directly before startup.
 .
 Custom homepage support.
 .
 Qubes integration.
 .
 Sanity tests:
  - Aborts if detected being run as root.
  - Aborts in Qubes TemplateVM.
  - Aborts in Qubes DVM Template.
  - Waits for Qubes mount dirs and gui agent being ready.
 .
 In Qubes AppVM copies browser from root image to private image at first start.
 .
 Tor Browser documentation by Whonix.
 .
  - https://www.whonix.org/wiki/Tor_Browser
  - https://www.whonix.org/wiki/Tor_Browser/Advanced_Users
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


