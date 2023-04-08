---
layout: default
title: corridor
nav_order: 315
parent: binary-kfreebsd-amd64
grand_parent: bullseye-testers main
---

**Package:** corridor

**Version:** 2:0.11.8.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  100

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/rustybird/corridor](https://github.com/rustybird/corridor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/c/corridor/corridor_0.11.8.2-1_all.deb

**Size:**  100

**Sha256:**  79646aa2c1ebb1da5ac13db89a81128d5fa4ef724ef42df58b72b6171d904b1f

**Sha1:**  e6eeffce15739ef8c4f6f2f176276ee0add30401

**Md5sum:**  de6d9e08ac1a56dca3382e332103c346

**Description:** Tor traffic whitelisting gateway
 There are several transparently torifying gateways. They suffer from the same
 problems:
 .
  - It's tricky to isolate circuits and issue NEWNYM signals, especially if
  multiple client computers are involved.
  - Any garbage software can pump identifiers into "anonymous" circuits, and
  get itself exploited by malicious exit nodes.
  - Trust is centralized to the gateway, which is bad enough when used by one
  person, and just inappropriate when shared with strangers.
 .
 corridor takes a different approach. It allows only connections to Tor relays
 to pass through (no clearnet leaks!), but client computers are themselves
 responsible for torifying their own traffic. In other words, it is a filtering
 gateway, not a proxying gateway.
 .
 You can think of it as defense in depth for your vanilla Tor Browser or Tails,
 for your beautiful scary experimental Qubes proxying schemes, etc. Or invite
 the hood to use your Wi-Fi without getting into trouble.


