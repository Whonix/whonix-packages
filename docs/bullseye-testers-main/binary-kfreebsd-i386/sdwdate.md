---
layout: default
title: sdwdate
nav_order: 317
parent: binary-kfreebsd-i386
grand_parent: bullseye-testers main
---

**Package:** sdwdate

**Version:** 3:21.6-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  305

**Recommends:**  timesanitycheck, bootclockrandomization

**Conficts:**  time-daemon

**Replaces:**  

**Provides:**  time-daemon

**Homepage:**  [https://github.com/Whonix/sdwdate](https://github.com/Whonix/sdwdate)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/sdwdate/sdwdate_21.6-1_all.deb

**Size:**  305

**Sha256:**  30a03475013a081f919e28b1c554be615f2d6f33aef9b514401a1a0ab6db6144

**Sha1:**  0e5b977da01dafd877b53b580f18ef34534ba3f8

**Md5sum:**  5ad467fd1e4b984c003dc4c538da297b

**Description:** Secure Distributed Network Time Synchronization
 Time keeping is crucial for security, privacy, and anonymity. Sdwdate is a Tor
 friendly replacement for rdate and ntpdate that sets the system's clock by
 communicating via onion encrypted TCP with Tor onion webservers.
 .
 At randomized intervals, sdwdate connects to a variety of webservers and
 extracts the time stamps from http headers (RFC 2616).
 Using sclockadj option, time is gradually adjusted preventing bigger clock
 jumps that could confuse logs, servers, Tor, i2p, etc.
 .
 This package contains the sdwdate time fetcher and daemon. No
 installation on remote servers required. To avoid conflicts, this daemon
 should not be enabled together with ntp or tlsdated.


