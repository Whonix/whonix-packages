---
layout: default
title: tb-updater
nav_order: 325
parent: binary-ppc64
grand_parent: bullseye-testers main
---

**Package:** tb-updater

**Version:** 3:25.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  297

**Recommends:**  tb-starter, icon-pack-dist, helper-scripts

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/tb-updater](https://github.com/Whonix/tb-updater)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tb-updater/tb-updater_25.4-1_all.deb

**Size:**  297

**Sha256:**  08dfc72c73392149fe8c7ff9783f99c6393d4a8d3dccb4714792c8c16f74e9ff

**Sha1:**  08f07c1f0e8b5a0cdc75b8f41e7d5d39e7fc371a

**Md5sum:**  7b7118e4398d31423ec049de55d98ea8

**Description:** Tor Browser Downloader by Whonix developers
 Automates download and verification of Tor Browser from The Tor Project's
 website. Useful for initial installation of Tor Browser, clean
 re-installations of Tor Browser and keeping newly created Qubes AppVMs
 inherited from updated Qubes TemplateVMs can ship up to date versions of
 Tor Browsers.
 .
 Incapable of preserving of updating and preserving user data. Use
 Tor Browser's internal updater for that purpose. Notifies about already
 exiting installations of Tor Browser. Renamed rather than deletes old versions
 of Tor Browsers to avoid user data loss.
 .
 Has a cli and a gui mode. Can auto detect latest version numbers or use user
 configured version numbers. Comes with a download confirmation screen that
 lets users choose which version to download. [1] Has a installation
 confirmation screen [2] that enables users to detect indefinite freeze and
 rollback attacks.
 .
 Integrates well with tb-starter, tb-default-browser and
 open-link-confirmation package as well as with Qubes.
 .
 Without the helper-scripts package installed, the GUI will not move the
 progress bar.
 .
 If you have the helper-scripts package installed, it will show a nicer
 progress bar when run in terminal and more meaningful curl exit code
 messages, when curl failed.
 .
 When having the helper-scripts package installed (recommended for
 Anonymity Distributions), Tor Browser Downloader will check, that Tor is
 enabled, that no package manager is currently running and that Tor finished
 bootstrapping before download attempts.
 .
 Supports being run inside chroot and from Debian maintainer postinst script.
 .
 Qubes integration:
 .
  - Up-to-date browser versions made available to freshly created AppVMs and
 DispVMs.
  - In DispVM mounts browser folder which resides in root image to user home
 folder rather than copying for faster browser startup.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.
 .
 [1] https://www.whonix.org/wiki/Tor_Browser#Download_Confirmation_Screen
 [2] https://www.whonix.org/wiki/Tor_Browser#Installation_Confirmation_Screen


