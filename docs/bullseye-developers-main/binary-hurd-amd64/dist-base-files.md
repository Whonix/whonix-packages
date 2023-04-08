---
layout: default
title: dist-base-files
nav_order: 111
parent: binary-hurd-amd64
grand_parent: bullseye-developers main
---

**Package:** dist-base-files

**Version:** 3:8.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  78

**Recommends:**  

**Conficts:**  anon-base-files

**Replaces:**  anon-base-files

**Provides:**  anon-base-files

**Homepage:**  [https://github.com/Whonix/dist-base-files](https://github.com/Whonix/dist-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/dist-base-files/dist-base-files_8.8-1_all.deb

**Size:**  78

**Sha256:**  7ef2a56cfc7cd1f0ea3c65091f162299ba64752786921ac21caec0005002e3f6

**Sha1:**  c4f5b522b61a8cbe931107a771e13aae3d111fbc

**Md5sum:**  90b3a0348633b76ee713be54c96f64dc

**Description:** base files for distributions
 Creates user `user` with password `changeme` (not in Qubes).
 That is if user `user` is not existing yet.
 And if it does create user `user` it also locks the root account.
 Therefore root account locking effectively only happens in new
 builds not having user `user` already created.
 .
 Adds user `user` to groups `cdrom`, `audio`, `dip`, `sudo`, `plugdev`.
 .
 Ships a systemd unit file dist-skel-first-boot.service
 which runs `/usr/libexec/helper-scripts/first-boot-skel`
 (part of helper-scripts) package.
 .
 Simplifies sudo default lecture to only showing the default password once.
 .
 Creates version file `/var/lib/dist-base-files/build_version`.
 .
 Default shell: Sets default shell for user `user` to `zsh`.
 (Unless file `/etc/no-shell-change` exists.)
 `debian/dist-base-files.postinst`
 .
 This package gets installed by default in both, Kicksecure and Whonix.


