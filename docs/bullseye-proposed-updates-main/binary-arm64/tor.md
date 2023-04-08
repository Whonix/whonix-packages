---
layout: default
title: tor
nav_order: 204
parent: binary-arm64
grand_parent: bullseye-proposed-updates main
---

**Package:** tor

**Version:** 0.4.7.13-1~d11.bullseye+1

**Architecture:**  arm64

**Maintainer:**  Peter Palfrader <weasel@debian.org>

**Installed_size:**  5521

**Recommends:**  logrotate, tor-geoipdb, torsocks

**Conficts:**  libssl0.9.8 (<< 0.9.8g-9)

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.torproject.org/](https://www.torproject.org/)

**Priority:**  optional

**Section:** net

**Filename:**  pool/main/t/tor/tor_0.4.7.13-1~d11.bullseye+1_arm64.deb

**Size:**  5521

**Sha256:**  d29218c8d32a122594f67e81bba2838beebc820e2cfcf79df3fee7fc1c4153c7

**Sha1:**  78cfd45848a9468f6141d772b37f7770be349a06

**Md5sum:**  47b9da8e5f3d8948b0f55f84c91a99bc

**Description:** anonymizing overlay network for TCP
 Tor is a connection-based low-latency anonymous communication system.
 .
 Clients choose a source-routed path through a set of relays, and
 negotiate a "virtual circuit" through the network, in which each relay
 knows its predecessor and successor, but no others. Traffic flowing
 down the circuit is decrypted at each relay, which reveals the
 downstream relay.
 .
 Basically, Tor provides a distributed network of relays. Users bounce
 their TCP streams (web traffic, ftp, ssh, etc) around the relays, and
 recipients, observers, and even the relays themselves have difficulty
 learning which users connected to which destinations.
 .
 This package enables only a Tor client by default, but it can also be
 configured as a relay and/or a hidden service easily.
 .
 Client applications can use the Tor network by connecting to the local
 socks proxy interface provided by your Tor instance. If the application
 itself does not come with socks support, you can use a socks client
 such as torsocks.
 .
 Note that Tor does no protocol cleaning on application traffic. There
 is a danger that application protocols and associated programs can be
 induced to reveal information about the user. Tor depends on Torbutton
 and similar protocol cleaners to solve this problem. For best
 protection when web surfing, the Tor Project recommends that you use
 the Tor Browser Bundle, a standalone tarball that includes static
 builds of Tor, Torbutton, and a modified Firefox that is patched to fix
 a variety of privacy bugs.


