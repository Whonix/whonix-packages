---
layout: default
title: tor
nav_order: 16
parent: binary-i386
grand_parent: bullseye main
---

**Package:** tor

**Version:** 0.4.7.13-1~d11.bullseye+1

**Architecture:**  i386

**Maintainer:**  Peter Palfrader <weasel@debian.org>

**Installed_size:**  6109

**Recommends:**  logrotate, tor-geoipdb, torsocks

**Conficts:**  libssl0.9.8 (<< 0.9.8g-9)

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.torproject.org/](https://www.torproject.org/)

**Priority:**  optional

**Section:** net

**Filename:**  pool/main/t/tor/tor_0.4.7.13-1~d11.bullseye+1_i386.deb

**Size:**  6109

**Sha256:**  a705b766764f55dbf07fbd9853ea10ca66cb929af86b9632611f2aae90f76bda

**Sha1:**  9fccdad1a9389a1499e7150348f17bbc2bb46f01

**Md5sum:**  8e07ccb1769a24378f0d9a6dfcefb392

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


