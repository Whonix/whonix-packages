---
layout: default
title: uwt
nav_order: 18
parent: binary-kfreebsd-amd64
grand_parent: bullseye main
---

**Package:** uwt

**Version:** 3:7.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  113

**Recommends:**  

**Conficts:**  diverts-etc++tor++torsocks.conf, diverts-usr++bin++apt, diverts-usr++bin++apt-file, diverts-usr++bin++apt-get, diverts-usr++bin++aptitude-curses, diverts-usr++bin++curl, diverts-usr++bin++dnf-3, diverts-usr++bin++git, diverts-usr++bin++gpg, diverts-usr++bin++gpg2, diverts-usr++bin++mixmaster-update, diverts-usr++bin++onionshare, diverts-usr++bin++onionshare-gui, diverts-usr++bin++rawdog, diverts-usr++bin++ricochet, diverts-usr++bin++ssh, diverts-usr++bin++wget, diverts-usr++bin++wormhole, diverts-usr++bin++yum, diverts-usr++bin++yumdownloader

**Replaces:**  

**Provides:**  diverts-etc++tor++torsocks.conf, diverts-usr++bin++apt, diverts-usr++bin++apt-file, diverts-usr++bin++apt-get, diverts-usr++bin++aptitude-curses, diverts-usr++bin++curl, diverts-usr++bin++dnf-3, diverts-usr++bin++git, diverts-usr++bin++gpg, diverts-usr++bin++gpg2, diverts-usr++bin++mixmaster-update, diverts-usr++bin++onionshare, diverts-usr++bin++onionshare-gui, diverts-usr++bin++rawdog, diverts-usr++bin++ricochet, diverts-usr++bin++ssh, diverts-usr++bin++wget, diverts-usr++bin++wormhole, diverts-usr++bin++yum, diverts-usr++bin++yumdownloader

**Homepage:**  [https://github.com/Whonix/uwt](https://github.com/Whonix/uwt)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/u/uwt/uwt_7.0-1_all.deb

**Size:**  113

**Sha256:**  b298751e2b3932a8381688586a157144ae1c6aac52538c38e49d08546134b096

**Sha1:**  72788141f3d2530c9bf17737ac3ce5a35fd90604

**Md5sum:**  2f236e57affaa0cbe012ecfd759db6c3

**Description:** Use Applications over Tor with Stream Isolation and Time Privacy
 Can add "torsocks" and/or "timeprivacy" before invocation of applications when
 configured to do so. For example, when simply typing "apt-get" instead of
 "torsocks apt-get", "apt-get" can still be routed over Tor.
 .
 The uwt package comes with the following applications pre-configured to use
 uwtwrapper, Tor and stream isolation:
  - apt
  - apt-file
  - apt-get
  - aptitude-curses
  - curl
  - git
  - gpg
  - gpg2
  - mixmaster-update
  - rawdog
  - ssh
  - wget
  - yum
  - yumdownloader
  - wormhole
 .
 To circumvent a uwt wrapper on a by case base, you append ".anondist-real" to
 the command, for example "apt-get.anondist-real". You can also deactivate
 specific or all uwt wrappers by using the stackable .d-style configuration
 folder /etc/uwt.d.
 .
 Uwt can only work only as good as torsocks. If torsocks is unable to route all
 of an application's traffic over Tor, ex. if there is an leak, there will
 also be one when using uwt. For that reason, it is recommended to use
 Anonymity Distributions, that prevent such leaks.
 .
 If an applications has native support for socks proxy settings, those should
 be preferred over uwt. Also refer to the TorifyHOWTO and your distribution's
 documentation.
 .
 Timeprivacy can keep your time private. You can create wrappers for
 applications and timeprivacy will feed those applications with a fake time,
 which obfuscates at which time you really used that applications (such as when
 you made the git commit or when you signed that document). It does NOT set
 your time zone to UTC.
 .
 This package is probably most useful for Anonymity Distributions.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


