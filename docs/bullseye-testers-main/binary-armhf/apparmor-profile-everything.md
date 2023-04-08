---
layout: default
title: apparmor-profile-everything
nav_order: 307
parent: binary-armhf
grand_parent: bullseye-testers main
---

**Package:** apparmor-profile-everything

**Version:** 3:7.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  165

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-everything/apparmor-profile-everything_7.4-1_all.deb

**Size:**  165

**Sha256:**  071e42873c1d9382be3c7358d3a3f67c0fc38518380a4a6b347eb429b66e90e1

**Sha1:**  086166883ad4be8af276897165333f33741b0968

**Md5sum:**  6f3a7bfb3ccd7062c27eea0744903607

**Description:** Full system AppArmor policy
 This is an AppArmor policy to confine all user space processes on the system which
 allows one to enforce a strong security model and follow principle of least privilege.
 An AppArmor policy for the init, systemd is loaded in the initramfs which then
 applies to all other processes. Specific policies for many system services/applications
 are also enforced.
 .
 This follows design ideas already present in other operating systems such as Android
 and attempts to make something similar available on desktop Linux.
 .
 In addition to locking down user space, this also protects the kernel as it restricts
 access to kernel interfaces like `/proc` or `/sys`, making kernel pointer and other
 leaks much less likely.
 .
 This does not and cannot confine the kernel or initramfs.
 .
 This is expected to be used in combination with other security technologies such as
 a hardened kernel, strong sandboxing architecture, verified boot and so on.
 .
 apparmor-profile-everything supports different boot modes: aadebug and superroot.
 aadebug allows certain permissions necessary for advanced debugging and superroot
 relaxes the policy substantially, even making bypasses possible. It is highly
 recommended to stick to the default boot mode.
 .
 It also contains a wrapper to restrict apt as apt requires permissions that may
 be abused to circumvent the policy. When updating or installing applications, you
 must use the `rapt` command.
 .
 This is still in development and breakage is likely. This should only be used by
 developers for now.
 .
 For now, please only use this development discussion forum thread:
 https://forums.whonix.org/t/apparmor-for-complete-system-including-init-pid1-systemd-everything-full-system-mac-policy/8339
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


