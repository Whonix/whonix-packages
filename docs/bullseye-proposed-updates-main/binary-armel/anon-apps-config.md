---
layout: default
title: anon-apps-config
nav_order: 206
parent: binary-armel
grand_parent: bullseye-proposed-updates main
---

**Package:** anon-apps-config

**Version:** 3:7.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  222

**Recommends:**  icon-pack-dist

**Conficts:**  diverts-usr++lib++xchat++plugins++perl.so, diverts-usr++lib++xchat++plugins++python.so, diverts-usr++lib++xchat++plugins++tcl.so, diverts-usr++share++gajim++plugins++plugin+-+installer+++-++-+init+-++-+.py

**Replaces:**  anon-gpg-tweaks, kde-apper-no-autoupdate, kde-kdm-autologin, pkg-manager-longer-timeouts, pkg-manager-no-autoupdate, timezone-utc, xchat-improved-privacy

**Provides:**  diverts-usr++lib++xchat++plugins++perl.so, diverts-usr++lib++xchat++plugins++python.so, diverts-usr++lib++xchat++plugins++tcl.so, diverts-usr++share++gajim++plugins++plugin+-+installer+++-++-+init+-++-+.py

**Homepage:**  [https://github.com/Whonix/anon-apps-config](https://github.com/Whonix/anon-apps-config)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-apps-config/anon-apps-config_7.7-1_all.deb

**Size:**  222

**Sha256:**  26430d02711d52335f1d95fc4821e342b3600b1a4b14ad5c2fe50a24fc4f2255

**Sha1:**  9adb00657a01e3e60b4ee6bfab891595a5f02a6a

**Md5sum:**  18d9828d0bb13527681812dddaccb438

**Description:** anonymity, privacy and security settings pre-configuration
 Most settings take effect for newly created user account onlys, and not
 for existing user accounts.
 .
 Sets timezone to UTC.
 .
 Enables Menubar in Dolphin by default.
 .
 gnupg configuration for Anonymity Distributions:
  * Sets `use-tor` in `/etc/skel/.gnupg/dirmngr.conf`.
  * Ships Thunderbird torbirdy configuration file
 `/etc/thunderbird/pref/30_whonix.js` that allows torified keyserver access.
  * Deactivates KGpg's first run wizard. Disables tip of the day.
  Disables KGpg's systray. Disables key server. Reference:
  "High-risk users should stop using the keyserver network immediately."
 .
 Double click instead of single click in KDE.
 .
 Deactivates maximize windows when moved to the top.
 In context of anonymity it might be better not to maximize the browser window
 (https://trac.torproject.org/projects/tor/ticket/7255).
 To prevent users from accidentally maximizing their browser window, it is
 better when KDE's feature to maximize windows when moved to the top is
 disabled.
 .
 Deactivates KDE's system sounds.
 .
 Disables KDE graphics effects. Disables some background processes.
 .
 Stream Isolation (proxy) settings for KDE apps for Anonymity Distributions
 Configures global proxy settings, which acts as a fallback if no other proxy
 settings are set, for KDE applications to socks 10.152.152.10:9122.
 IP HARDCODED above but no need to change since it is description only.
 Otherwise unconfigured KDE applications would use no proxy settings
 (Transparent Proxying) if the anonymity distribution features a transparent
 proxy.
 Useful to improve stream isolation.
 On the other hand, anonymity distributions not featuring transparent proxying
 should probably not install this package by default, because then unconfigured
 KDE applications should by default not be able to connect.
 .
 Sets Unlimited Scrollback in Konsole.
 .
 Disables klipper clipboard history.
 .
 Deactivates automatic updates for Package Manager APT and Apper
 Useful in context of networks with limited traffic quota, slow networks and
 anonymity distributions.
 In latter case, the default automatic updates interval would be too
 predictable (expectable amount of traffic every X), thus eventually be
 vulnerable for traffic fingerprinting.
 Disabling Apper automatic updates only takes effect for newly created user
 accounts. Not for existing user accounts. This is most useful to help Linux
 distribution maintainers setting divergent defaults.
 .
 Longer Timeouts for Package Manager APT
 Raising timeout and retries using configuration snippet. Useful in context of
 slow networks and anonymity distributions.
 .
 Ships a configuration file /etc/apt/apt.conf.d/90longer-timeouts to configure
 apt-get.
 .
 Ships a configuration file /etc/skel/.config/vlc/vlcrc to configure VLC to not
 ask for network policy at start and sets vout=xcb_x11 to enable VM
 compatibility out-of-the-box.
 .
 Disabled gajim update manager by default for better security since it does not
 verify software signatures by hiding file
 /usr/share/gajim/plugins/plugin_installer/__init__.py using
 'config-package-dev' 'hide'.
 .
 Disables systemd-resolved during boot unless file /etc/dns-enable exists.
 .
 Disables systemd-resolved fallback DNS (which by default is set to Google).
 .
 Removes capabilities from `/bin/ping` if
 [security-misc](https://github.com/Whonix/security-misc) is
 installed as ping doesn't work with Tor anyway and its capabilities are just
 unneeded attack surface.
 .
 Create a dummy Tor binary '/home/user/.local/share/Bisq/btc_mainnet/tor/tor'
 to avoid Tor over Tor.
 .
 Improves HexChat Privacy Settings
  * As per:
  https://gitlab.torproject.org/legacy/trac/-/wikis/doc/TorifyHOWTO/XChat
  * Moves the following files:
  - `/usr/lib/xchat/plugins/python.so`
  - `/usr/lib/xchat/plugins/tcl.so`
  - `/usr/lib/xchat/plugins/perl.so`
 to `/usr/share/anon-apps-config`, so these plugins get disabled by
 default.
 .
 Due to technical limitations some settings only take effect for applications
 being started for the very first time, i.e. when the user config of that
 application in the user's home folder does not exist yet. Works best for new
 user accounts.
 .
 This package is most useful to help Linux distribution maintainers setting
 divergent defaults.


