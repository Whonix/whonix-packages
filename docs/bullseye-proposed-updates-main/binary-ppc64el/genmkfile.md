---
layout: default
title: genmkfile
nav_order: 228
parent: binary-ppc64el
grand_parent: bullseye-proposed-updates main
---

**Package:** genmkfile

**Version:** 3:12.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  108

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/genmkfile](https://github.com/Whonix/genmkfile)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/g/genmkfile/genmkfile_12.2-1_all.deb

**Size:**  108

**Sha256:**  5cf4b851aa4ceeecbb3bb19f383c8fba0fc28843ff4d6577d0b86a7ba9ab533e

**Sha1:**  39dc40d6f945cbcb2f2b9556ab1513d3ff69ae05

**Md5sum:**  c577f2b9143deb239d333bb4344ec353

**Description:** Generic Makefile
 Makes packaging simpler. No more need to manually maintain
 'make install' targets or distribution specific install files such as
 debian/pkg-name.install.
 .
 Files in etc/... in root source folder will be installed to /etc/..., files in
 usr/... will be installed to /usr/... and so forth. This should make renaming,
 moving files around, packaging, etc. very simple. Packaging of most packages
 can look very similar.
 .
 Provides common make targets such as 'make install', 'make dist',
 'make installsim', 'make installcheck', 'make uninstall',
 'make uninstallcheck', 'make distclean'.
 .
 Very extensible through
 file ./make-helper-overrides.bsh or
 folder ./make-helper-overrides.d.
 By using overrides, any make target can be easily extended using pre or post
 hooks or replaced.
 Override files which are executable will be used.
 Override files which are not executable will be skipped.
 .
 Contains a minimal Makefile while the heavy lifting is done by a bash script
 make-helper.bsh.
 .
 Building for multiple platforms possible, example:
 export make_cross_build_platform_list="i386 amd64"
 .
 Can call with lintian (static analysis tool for Debian packages).
 By default it will be using lintian if installed while failing open
 (non-zero exit code).
 lintian can be disabled.
 export make_use_lintian=false
 Or can be configured to fail closed (non-zero exit code).
 export make_use_lintian=true
 .
 Can build packages without chroot using debuild (default) or inside chroot
 using cowbuilder. To enable cowbuilder, use:
 export make_use_cowbuilder=true
 .
 Supports signing packages using debsign.
 (sign a Debian .changes and .dsc file pair using GPG)
 export make_use_debsign=true


