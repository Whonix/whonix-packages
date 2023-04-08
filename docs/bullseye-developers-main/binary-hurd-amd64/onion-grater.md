---
layout: default
title: onion-grater
nav_order: 111
parent: binary-hurd-amd64
grand_parent: bullseye-developers main
---

**Package:** onion-grater

**Version:** 3:10.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  126

**Recommends:**  

**Conficts:**  control-port-filter

**Replaces:**  control-port-filter-python

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Dev/CPFP](https://www.whonix.org/wiki/Dev/CPFP)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/o/onion-grater/onion-grater_10.9-1_all.deb

**Size:**  126

**Sha256:**  a45c54177f94f53ad35c7cc4f038ca6c51ef93b2d790f5d2504a878bef2b64bb

**Sha1:**  537009d18460629cba2b32456620fe8e265411fc

**Md5sum:**  59d58c64bff69c3754201653347ba44b

**Description:** Whitelisting filter for dangerous Tor control protocol commands
 Filters out Tor control protocol commands that are dangerous for anonymity
 such as GETINFO ADDRESS using a whitelist. Acts as a proxy between the client
 application and Tor.
 .
 For example it allows using Tor Browser's New Identity feature on Anonymity
 Distribution Workstations, fixes Tor Browser's about:tor default homepage and
 Tor Button status indicator without exposing commands that are dangerous for
 anonymity.
 .
 This package is supposed to be installed on Anonymity Distributions.
 .
 It seamlessly integrates if the anon-ws-disable-stacked-tor package
 is installed on a Anonymity Distribution Workstations. For example it then
 allows running a unmodified Tor Browser Bundle from The Tor Project without
 Tor over Tor and with functional New Identity and about:tor.
 .
 This control port filter is written in Python. The original Python code
 was forked from the Tails version of control port filter.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.


