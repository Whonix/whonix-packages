---
layout: default
title: hardened-malloc
nav_order: 4
parent: binary-amd64
grand_parent: bullseye main
---

**Package:** hardened-malloc

**Version:** 0:11.1-1

**Architecture:**  amd64

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  147

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/GrapheneOS/hardened_malloc](https://github.com/GrapheneOS/hardened_malloc)

**Priority:**  optional

**Section:** libs

**Filename:**  pool/main/h/hardened-malloc/hardened-malloc_11.1-1_amd64.deb

**Size:**  147

**Sha256:**  edee8c7600aa3c1d2dac547b4c0fc59af4a6d4efc12372cb4ee1ec97f6752b4e

**Sha1:**  66e24386d837e735a38a31e57cb2f700206ce8a5

**Md5sum:**  9c8f33caf52f2e5a20a968510388074d

**Description:** security-focused general purpose memory allocator
 This is a security-focused general purpose memory allocator providing the
 malloc API along with various extensions. It provides substantial hardening
 against heap corruption vulnerabilities. The security-focused design also
 leads to much less metadata overhead and memory waste from fragmentation than
 a more traditional allocator design. It aims to provide decent overall
 performance with a focus on long-term performance and memory usage rather than
 allocator micro-benchmarks. It offers scalability via a configurable number of
 entirely independently arenas, with the internal locking within arenas further
 divided up per size class.
 .
 It can be added as a preloaded library using /etc/ld.so.preload.
 .
 Ships two files:
 .
  * [1] /usr/lib/libhardened_malloc.so/libhardened_malloc.so
  * [2] /usr/lib/libhardened_malloc.so/libhardened_malloc-light.so
 .
 [1] Was compiled with Hardened Malloc Default compilation parameters.
 .
 [2] Was compiled with Hardened Malloc Light compilation parameters.


