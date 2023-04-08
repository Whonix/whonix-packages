---
layout: default
title: hardened-kernel
nav_order: 313
parent: binary-i386
grand_parent: bullseye-testers main
---

**Package:** hardened-kernel

**Version:** 3:4.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  442

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/hardened-kernel](https://github.com/Whonix/hardened-kernel)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/h/hardened-kernel/hardened-kernel_4.0-1_all.deb

**Size:**  442

**Sha256:**  963ed94b23fc984b0ac9b7df73add6ac9c39862dba90b3689fcefe1782b210de

**Sha1:**  f1562271f52d06110c7bd8de11e9482e28f63b65

**Md5sum:**  10824819d4e8267d8b8ea33124a8736e

**Description:** Hardened Kernel for Host and VMs
 This is a hardened kernel configuration for Whonix / Kicksecure.
 hardened-vm-kernel is designed specifically for virtual machines and
 hardened-host-kernel is designed for hosts.
 .
 Both configs try to have as many hardening options enabled as possible and
 have little attack surface. hardened-vm-kernel only has support for VMs
 and all other hardware options are disabled to reduce attack surface and
 compile time.
 .
 During installation of hardened-vm-kernel, it compiles the kernel on your own
 machine and does not use a pre-compiled kernel. This ensures the kernel
 symbols in the compiled image are completely unique which makes it far harder
 for kernel exploits. This is possible due to hardened-vm-kernel having only VM
 config options enabled which drastically reduces compile time.
 .
 During installation of hardened-host-kernel, the kernel is not compiled on
 your machine and it uses a pre-compiled kernel. This is because the host
 kernel needs most hardware options enabled to support most devices which makes
 compilation take a very long time.
 .
 The VM kernel is more secure than the host kernel due to having less attack
 surface and not being pre-compiled but if you want more security for the host,
 it is recommended to edit the hardened host config, enable only the hardware
 options you need and compile the kernel yourself. This makes the security of
 the host and VM kernel comparable.
 .
 Both configs were based on the default Debian config.
 .
 These kernels use the linux-hardened patch for further hardening. Custom
 hardening patches should be
 sent there.
 .
 This only supports LTS kernels as they have the least attack surface (stable
 kernels have more code and more bugs) and the best stability.
 .
 Build script /usr/share/hardened-vm-kernel/build does not run automatic yet.
 .
 Kernel does not get installed automatic yet.
 .
 See also development discussion:
 http://forums.whonix.org/t/kernel-recompilation-for-better-hardening


