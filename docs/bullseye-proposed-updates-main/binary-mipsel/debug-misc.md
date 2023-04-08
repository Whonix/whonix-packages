---
layout: default
title: debug-misc
nav_order: 222
parent: binary-mipsel
grand_parent: bullseye-proposed-updates main
---

**Package:** debug-misc

**Version:** 3:2.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  71

**Recommends:**  

**Conficts:**  

**Replaces:**  grub-output-verbose

**Provides:**  

**Homepage:**  [https://github.com/Whonix/debug-misc](https://github.com/Whonix/debug-misc)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/debug-misc/debug-misc_2.8-1_all.deb

**Size:**  71

**Sha256:**  734405700ec2c1e9a644c3b012d4fd9e7f748c95c6a5747b4545ec63a28f10bf

**Sha1:**  03e5abd8b2ea2964729cfc1cea622a22224df609

**Md5sum:**  c2326a39590fd23100f9e24698f99bcf

**Description:** Enables miscellaneous debug settings
 Ships a `/etc/default/grub.d/45_debug-misc.cfg` configuration file,
 that removes `quiet`, `loglevel=0` and `debugfs=off` from the
 `GRUB_CMDLINE_LINUX_DEFAULT` variable and adds `debug=vc` to the kernel
 boot parameter to enable verbose output during the initial ramdisk boot
 phase.
 .
 Undo debugging related `sysctl` settings by package `security-misc`.
 .
 Enables persistent systemd journal log.
 .
 Disables `/lib/systemd/coredump.conf.d/disable-coredumps.conf` by package
 `security-misc` by creating a symlink from
 `/etc/systemd/coredump.conf.d/disable-coredumps.conf` to `/dev/null`.
 `debian/debug-misc.links`
 .
 Disables `panic-on-oops`, `remove-system.map` by package `security-misc`.
 .
 `config-package-dev` `hide` `/etc/sysctl.d/30_silent-kernel-printk.conf` which
 kernel.printk to default as if security-misc would not have lowered verbosity.
 .
 Configure systemd `getty` service to not clear `tty`.
 `/lib/systemd/system/getty@tty.service.d/30_debug-misc.conf`
 .
 Coredumps are enabled.
 `/etc/security/limits.d/40_debug-misc.conf`
 .
 Coredumps may contain important information such as encryption keys or
 passwords. Package `security-misc` disables coredumps. Package `debug-misc`
 re-enables coredumps.
 .
 Contains a helper tool to cause a segfault for testing purposes.
 `segfault-build` creates `segfault-run`. Running `segfault-run` results in
 `segfault-run` terminating with a segfault. This is useful to test if
 coredump files are being generated when an application crashes.
 `/usr/sbin/segfault-build`
 `/usr/share/debug-misc/segfault.c`
 .
 For better usability, to ease debugging in case of issues.
 .
 For better security, this package should only be installed on specific
 machines that require debugging. Unfortunately, security and debugging are
 conflicting optimization goals.


