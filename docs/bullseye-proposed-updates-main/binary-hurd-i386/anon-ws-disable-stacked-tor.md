---
layout: default
title: anon-ws-disable-stacked-tor
nav_order: 212
parent: binary-hurd-i386
grand_parent: bullseye-proposed-updates main
---

**Package:** anon-ws-disable-stacked-tor

**Version:** 3:7.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  155

**Recommends:**  

**Conficts:**  diverts-etc++default++tor, diverts-usr++bin++tor, diverts-usr++sbin++tor

**Replaces:**  

**Provides:**  diverts-etc++default++tor, diverts-usr++bin++tor, diverts-usr++sbin++tor, obfs4proxy, obfsproxy, tor

**Homepage:**  [https://github.com/Whonix/anon-ws-disable-stacked-tor](https://github.com/Whonix/anon-ws-disable-stacked-tor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-ws-disable-stacked-tor/anon-ws-disable-stacked-tor_7.1-1_all.deb

**Size:**  155

**Sha256:**  76168e78fec5189a77c0ca255f67ffd8eb748c6342865bb5ed38c0430b6bbf5d

**Sha1:**  5f2742d8adc7ee7349589ef67315790d15829dfd

**Md5sum:**  fc1297e186975e61ffb75c3c69a94db0

**Description:** Prevents Tor over Tor in Anonymity Distribution Workstations
 Supposed to be installed on Workstations, which prevents installing the real
 Tor package from upstream (ex: Debian, The Tor Project) APT repositories. Its
 purpose is to prevent, running Tor over Tor.
 .
 It allows installation of packages, which depend on Tor, such as TorChat,
 parcimonie and torbrowser-launcher.
 .
 This package uses the "Provides: tor" field[1], which should avoid any kinds of
 conflicts, in case upstream releases a higher version of Tor. This won't work
 for packages, which depend on an explicit version of Tor (such as TorChat).
 This is non-ideal, since for example the torchat package will install Tor, but
 still acceptable, because of the following additional implementations.
 .
 Binaries eventually installed (by the tor Debian package) /usr/bin/tor as well
 as /usr/sbin/tor are replaced with a dummy wrapper that does nothing
 (dpkg-diverted using config-package-dev).
 .
 systemd-socket-proxyd listens on Tor's default ports. system Tor's
 127.0.0.1:9050, 127.0.0.1:9051 and TBB's 127.0.0.1:9150, 127.0.0.1:9051,
 which prevents the
 default Tor Browser Bundle or Tor package by The Tor Project from opening
 these default ports, which will result in Tor failing to open its listening
 port and therefore exiting, thus preventing Tor over Tor.
 .
 See also:
 .
 * https://www.whonix.org/wiki/Dev/anon-ws-disable-stacked-tor
 * https://tor.stackexchange.com/questions/427/is-running-tor-over-tor-dangerous
 .
 [1] See "7.5 Virtual packages - Provides" on
 http://www.debian.org/doc/debian-policy/ch-relationships.html
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


