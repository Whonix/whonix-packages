---
layout: default
title: usability-misc
nav_order: 315
parent: binary-kfreebsd-amd64
grand_parent: bullseye-testers main
---

**Package:** usability-misc

**Version:** 3:12.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  339

**Recommends:**  

**Conficts:**  

**Replaces:**  gpl-sources-download, grub-screen-resolution, scurl

**Provides:**  

**Homepage:**  [https://github.com/Whonix/usability-misc](https://github.com/Whonix/usability-misc)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/u/usability-misc/usability-misc_12.8-1_all.deb

**Size:**  339

**Sha256:**  4afef338a0cacab225879fb0d1bd92cc28e5f73e25f8084edad3914aa6fe6743

**Sha1:**  2400be47d822def0067e4b606bd72cc720b50a7f

**Md5sum:**  9a5c250430966bb407e5e2d8da3adb0d

**Description:** Misc usability improvements
 Creates user "user" if it does not already exist.
 .
 Creates folders /home/user/Downloads and /home/user/Pictures.
 .
 Adds user "user" to group libvirt as well as to group kvm.
 .
 Ships a file /etc/sudoers.d/user-passwordless that contains comments and
 "#user   ALL=(ALL:ALL) NOPASSWD:ALL". Lets user "user" easily run all
 commands without password. Disabled (out commented) by default.
 .
 Simplifies running OpenVPN as unprivileged user.
 .
 Ships a FoxyProxy add-on configuration file for use with Tor Browser.
 .
 Provides apt-get-noninteractive that is a simple wrapper around apt-get, that
 sets all required environment variables to make it interactive as well as to
 prevent systemd service starts and restarts during apt-get.
 .
 Sets mousepad as the default editor for environment variable VISUAL
 is unset and if mousepad is installed.
 .
 Disable sudo default lecture.
 /etc/sudoers.d/sudo-lecture-disable
 .
 Add pwfeedback to sudo Defaults so password asterisks are shown while typing.
 /etc/sudoers.d/pwfeedback
 .
 xfce4-terminal:
 .
  * Disables automatic scroll on output when manually scrolled up to make
 reading output such as "sudo journalctl -f" easier.  Automatic scroll on
 output still happening in default when not manually scrolling up beforehand
 first.
 .
  * Enables unlimited scrollback by default to avoid output from being
 truncated.
 .
 Ships gsudoedit, a wrapper to run sudoedit with a graphical editor.
 .
 Bisq workarond "sudo mkdir -p /usr/share/desktop-directories" as per
 https://github.com/bisq-network/bisq/issues/848
 .
 gpl_sources_download GPL'ed source code of all installed packages.
 Used damngpl to get a list of all GPL'ed packages, then downloads them using
 apt-get source.
 .
 SSL curl wrapper: Simple wrapper called scurl, that adds
 "--tlsv1.3 --proto =https" in front of all invocations of "curl" when
 running "scurl".
 .
 Sets 1024x768 as boot screen resolution
 Ships a /etc/default/grub.d/30_screen_resolution.cfg configuration file, that
 injects "vga=0x0317" into the GRUB_CMDLINE_LINUX_DEFAULT variable.


