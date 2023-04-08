---
layout: default
title: timesanitycheck
nav_order: 305
parent: binary-armel
grand_parent: bullseye-testers main
---

**Package:** timesanitycheck

**Version:** 3:5.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  45

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Dev/TimeSync](https://www.whonix.org/wiki/Dev/TimeSync)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/timesanitycheck/timesanitycheck_5.2-1_all.deb

**Size:**  45

**Sha256:**  867d8ec1dd6e53ec371a8514f7c406a4d8778b86d1bd13e5459643df540ba0a1

**Sha1:**  4b4f5f66286932e08dae7e8536660c4636c82b26

**Md5sum:**  1c2cdf8ec09a76256da357fd37b0e961

**Description:** Checks if the system clock is sane between build timestamp and expiration date
 Reports, if clock is sane and not slower than build timestamp or faster than
 expiration date (configurable, default currently set to 17 MAY 2033 10:00:00).
 .
 This should catch situations, where the host's clock is too much off (CMOS
 battery defect, user mistakenly set a very wrong date, etc.), resulting in
 network time synchronization tools (such as sdwdate) no longer being able to
 correct the clock; catch eventual bigger bugs in network time synchronization
 tools; and some types of attacks on network time synchronization.


