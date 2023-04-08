---
layout: default
title: whonix-gw-network-conf
nav_order: 121
parent: binary-mips
grand_parent: bullseye-developers main
---

**Package:** whonix-gw-network-conf

**Version:** 3:4.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  52

**Recommends:**  

**Conficts:**  diverts-etc++resolv.conf

**Replaces:**  anon-gw-dns-conf, kicksecure-network-conf

**Provides:**  diverts-etc++resolv.conf

**Homepage:**  [https://github.com/Whonix/whonix-gw-network-conf](https://github.com/Whonix/whonix-gw-network-conf)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/w/whonix-gw-network-conf/whonix-gw-network-conf_4.5-1_all.deb

**Size:**  52

**Sha256:**  2ca9869d81545503d5d0b2979400a4135aa30f57922d2639e5fab81fb68d4423

**Sha1:**  98608cd35eee6babe3c5f81fe66dc88186ab5a49

**Md5sum:**  cc1c8a7698dad3d8a4f02d691ca6bba5

**Description:** Network Configuration for Whonix-Gateway
 Includes etc/network/interfaces.d/30_non-qubes-whonix for
 Non-Qubes-Whonix-Gateway.
 .
 Sets up two network interfaces, an external one eth0 and an internal one eth1.
 .
 Provides /usr/share/whonix-gw-network-conf/network_internal_ip.txt.
 .
 DNS configuration Anonymity Linux Distribution Gateways
 .
  * Pointing /etc/resolv.conf to 127.0.0.1.
  * Whether a Anonymity Linux Distribution Gateway supports system DNS for its
 own traffic in the clear or anonymized mainly depends on the Gateway's
 firewall.
  * Routing the workstation's system DNS through the anonymizer (also known as
 Transparent DNS Proxy) or not is up to the Gateway's firewall as well.


