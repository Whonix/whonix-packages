---
layout: default
title: sandbox-app-launcher
nav_order: 131
parent: binary-s390x
grand_parent: bullseye-developers main
---

**Package:** sandbox-app-launcher

**Version:** 0:5.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  98

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/sandbox-app-launcher](https://github.com/Whonix/sandbox-app-launcher)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/sandbox-app-launcher/sandbox-app-launcher_5.7-1_all.deb

**Size:**  98

**Sha256:**  a3794c819dd3a56d5d3f004ec503ed3028a5f23e253262d90fee50f901ec7b04

**Sha1:**  5bc4cd7f1d0de03a0ce61cd1acac9b9ae404a446

**Md5sum:**  bcc5dc8d9842f8951f946aef858a5562

**Description:** application launcher to start apps in a restrictive sandbox
 sandbox-app-launcher runs each app as its own user, in a bubblewrap sandbox
 and confined by apparmor.
 .
 The directory, `/shared`, is shared across all app sandboxes to transfer
 files across.
 .
 This implements a permissions system to configure what apps can access.
 There are currently 5 available permissions:
 .
  * Network access
 .
  * Webcam access
 .
  * Microphone access
 .
  * Shared storage access (read-only or read-write)
 .
  * Dynamic native code execution
 .
 All apps the user installs will be automatically configured to run in
 the sandbox and a prompt will ask the user which permissions they wish to
 grant the application (not implemented yet).
 .
 Currently a WIP and not for actual use.


