---
layout: default
title: tirdad
nav_order: 103
parent: binary-amd64
grand_parent: bullseye-developers main
---

**Package:** tirdad

**Version:** 0:0.1.22-1

**Architecture:**  amd64

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  16

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/0xsirus/tirdad](https://github.com/0xsirus/tirdad)

**Priority:**  optional

**Section:** kernel

**Filename:**  pool/main/t/tirdad/tirdad_0.1.22-1_amd64.deb

**Size:**  16

**Sha256:**  c2f798d36e9a03e559aee43dd6009a94b1ce412db1c8dc7ed9b3e60a60d336dc

**Sha1:**  2910f8534baab146972ece64e8717c80e0fa1fbf

**Md5sum:**  1a11f9ece6c45c2409191b179953aaf7

**Description:** TCP ISN CPU Information Leak Protection
 TCP Initial Sequence Numbers Randomization to prevent TCP ISN based CPU
 Information Leaks.
 .
 The Linux kernel has a side-channel information leak bug.
 It is leaked in any outgoing traffic.
 This can allow side-channel attacks because sensitive information about
 a system's CPU activity is leaked.
 .
 It may prove very dangerous for long-running cryptographic operations. [A]
 .
 Research has demonstrated that it can be used for de-anonymization of
 location-hidden services. [1]
 .
 Clock skew,
 .
  - is leaked through TCP ISNs (Initial Sequence Number) by the Linux kernel.
  - can be remotely detected through observing ISNs.
  - can be induced by an attacker through producing load on the victim machine.
 .
 Quote Security researcher Steven J. Murdoch
 (University of Cambridge, Cambridge, UK) [B]
 .
 "What the Linux ISN leaks is the difference between two timestamps, not the
 timestamp itself. A difference lets you work out drift and skew, which can
 help someone fingerprint the computer hardware, its environment and load. Of
 course that only works if you can probe a computer, and maintain the same
 source/destination port and IP address."
 .
 Quote Mike Perry, developer at The Tor Project [A]:
 .
 "... it is worth complaining to the kernel developers for the simple
 reason that adding the 64ns timer post-hash probably *does* leak side channels
 about CPU activity, and that may prove very dangerous for long-running
 cryptographic operations (along the lines of the hot-or-not issue).
 Unfortunately, someone probably needs to produce more research papers before
 they will listen."
 .
 tirdad is a kernel module to hot-patch the Linux kernel
 to generate random TCP Initial Sequence Numbers for IPv4 TCP connections.
 .
 You can refer to this bog post to get familiar with the original issue:
 .
  - An analysis of TCP secure SN generation in Linux and its privacy issues
  - https://bitguard.wordpress.com/?p=982
 .
 This metapackage depends on tirdad-dkms.
 .
 References:
 .
  - [1] https://www.cl.cam.ac.uk/~sjm217/papers/ccs06hotornot.pdf
  - [2] http://caia.swin.edu.au/talks/CAIA-TALK-080728A.pdf
  - [3] http://www.cl.cam.ac.uk/~sjm217/papers/ih05coverttcp.pdf
  - [4] https://stackoverflow.com/a/12232126
  - [5] http://lxr.free-electrons.com/source/net/core/secure_seq.c?v=3.16
  - [6] https://trac.torproject.org/projects/tor/ticket/16659
  - [7] https://phabricator.whonix.org/T543
  - [A] https://trac.torproject.org/projects/tor/ticket/16659#comment:10
  - [B] https://trac.torproject.org/projects/tor/ticket/16659#comment:18


