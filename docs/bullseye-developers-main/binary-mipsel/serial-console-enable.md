---
layout: default
title: serial-console-enable
nav_order: 123
parent: binary-mipsel
grand_parent: bullseye-developers main
---

**Package:** serial-console-enable

**Version:** 3:3.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  30

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/serial-console-enable](https://github.com/Whonix/serial-console-enable)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/serial-console-enable/serial-console-enable_3.2-1_all.deb

**Size:**  30

**Sha256:**  279e15d5076f58001fe8e3b4e92223131553158b775336884c763d3a502e0e96

**Sha1:**  a9569e592ad8d5e4e81f428da1d673fcfcbb699e

**Md5sum:**  b0ec4e06361c656bf5d905cea8d3a172

**Description:** Enables serial console
 Ships a /etc/default/grub.d/30_serial_console.cfg configuration file, that
 enables serial console.
 .
 Enables /lib/systemd/system/getty.target.wants/serial-getty@ttyS0.service by
 creating a symlink from:
 /lib/systemd/system/serial-getty@.service
 to:
 /lib/systemd/system/getty.target.wants/serial-getty@ttyS0.service
 .
 Useful for serial console login such as into Whonix KVM VMs from the host
 operating system.
 .
 Forum discussion:
 https://forums.whonix.org/t/how-do-i-enter-the-whonix-shell-from-cli/7271
 .
 Safe to remove if you do not require serial console login such as:
 virsh console vm-name


