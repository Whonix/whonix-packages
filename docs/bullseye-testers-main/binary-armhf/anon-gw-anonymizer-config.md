---
layout: default
title: anon-gw-anonymizer-config
nav_order: 307
parent: binary-armhf
grand_parent: bullseye-testers main
---

**Package:** anon-gw-anonymizer-config

**Version:** 3:14.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  215

**Recommends:**  onion-grater

**Conficts:**  diverts-etc++apparmor.d++local++system+-+tor, diverts-etc++apparmor.d++local++usr.bin.obfsproxy, diverts-etc++default++tor, diverts-etc++tor++torrc

**Replaces:**  anon-gw-leaktest, ipv4-forward-disable, ipv6-disable

**Provides:**  diverts-etc++apparmor.d++local++system+-+tor, diverts-etc++apparmor.d++local++usr.bin.obfsproxy, diverts-etc++default++tor, diverts-etc++tor++torrc

**Homepage:**  [https://github.com/Whonix/anon-gw-anonymizer-config](https://github.com/Whonix/anon-gw-anonymizer-config)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-gw-anonymizer-config/anon-gw-anonymizer-config_14.7-1_all.deb

**Size:**  215

**Sha256:**  673252253f0e523cf0da633dac2115b4442262cba8bd98d735f00d114ba4ca24

**Sha1:**  1ee46a92c016525c562c16e09b0ba43eb1acec3b

**Md5sum:**  bad062faecb176e0bbd024af0e6762e4

**Description:** Tor Configuration and Tweaks for Anonymity Distributions
 Tor config file with distribution defaults (for stream isolation, etc.),
 example user configurations and other tweaks required. The Tor binary
 itself does not get modified.
 .
 Deactivates IPv4 forwarding using /etc/sysctl.d/
 IPv4 forwarding is not required for a Tor based Anonymity Distribution
 Gateways. Deactivating it as defense in depth to prevent leaks.
 .
 Deactivates IPv6 using /etc/sysctl.d/
 There are no IPv6 Anonymity Distribution Gateways featuring an IPv6 firewall
 yet. Therefore deactivating it to prevent leaks.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


