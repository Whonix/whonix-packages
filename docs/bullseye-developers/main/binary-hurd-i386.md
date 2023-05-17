---
layout: default
title: binary-hurd-i386
nav_order: 10
parent: main
grand_parent: bullseye-developers
---

# bullseye-developers main packages for binary-hurd-i386


  1. [anon-apps-config](#anon-apps-config)
  

  2. [anon-apt-sources-list](#anon-apt-sources-list)
  

  3. [anon-connection-wizard](#anon-connection-wizard)
  

  4. [anon-gw-anonymizer-config](#anon-gw-anonymizer-config)
  

  5. [anon-gw-base-files](#anon-gw-base-files)
  

  6. [anon-shared-build-apt-sources-tpo](#anon-shared-build-apt-sources-tpo)
  

  7. [anon-ws-base-files](#anon-ws-base-files)
  

  8. [anon-ws-disable-stacked-tor](#anon-ws-disable-stacked-tor)
  

  9. [apparmor-profile-dist](#apparmor-profile-dist)
  

  10. [apparmor-profile-everything](#apparmor-profile-everything)
  

  11. [apparmor-profile-hexchat](#apparmor-profile-hexchat)
  

  12. [apparmor-profile-thunderbird](#apparmor-profile-thunderbird)
  

  13. [apparmor-profile-torbrowser](#apparmor-profile-torbrowser)
  

  14. [apparmor-profiles-kicksecure](#apparmor-profiles-kicksecure)
  

  15. [binaries-freedom](#binaries-freedom)
  

  16. [bindp](#bindp)
  

  17. [bootclockrandomization](#bootclockrandomization)
  

  18. [corridor](#corridor)
  

  19. [damngpl](#damngpl)
  

  20. [deb.torproject.org-keyring](#deb.torproject.org-keyring)
  

  21. [debug-misc](#debug-misc)
  

  22. [desktop-config-dist](#desktop-config-dist)
  

  23. [desktop-config-dist-dependencies](#desktop-config-dist-dependencies)
  

  24. [developer-meta-files](#developer-meta-files)
  

  25. [dist-base-files](#dist-base-files)
  

  26. [dummy-dependency](#dummy-dependency)
  

  27. [dummy-dependency-apparmor-profiles-kicksecure](#dummy-dependency-apparmor-profiles-kicksecure)
  

  28. [dummy-dependency-bindp](#dummy-dependency-bindp)
  

  29. [dummy-dependency-electrum](#dummy-dependency-electrum)
  

  30. [dummy-dependency-hardened-electrum](#dummy-dependency-hardened-electrum)
  

  31. [dummy-dependency-hardened-malloc](#dummy-dependency-hardened-malloc)
  

  32. [dummy-dependency-kloak](#dummy-dependency-kloak)
  

  33. [dummy-dependency-tirdad](#dummy-dependency-tirdad)
  

  34. [dummy-dependency-xorg-vm](#dummy-dependency-xorg-vm)
  

  35. [genmkfile](#genmkfile)
  

  36. [gpg-bash-lib](#gpg-bash-lib)
  

  37. [grub-live](#grub-live)
  

  38. [grub-live-dracut](#grub-live-dracut)
  

  39. [grub-live-initramfs-tools](#grub-live-initramfs-tools)
  

  40. [hardened-kernel](#hardened-kernel)
  

  41. [helper-scripts](#helper-scripts)
  

  42. [icon-pack-dist](#icon-pack-dist)
  

  43. [initializer-dist](#initializer-dist)
  

  44. [kicksecure-base-files](#kicksecure-base-files)
  

  45. [kicksecure-cli](#kicksecure-cli)
  

  46. [kicksecure-cli-host](#kicksecure-cli-host)
  

  47. [kicksecure-cli-vm](#kicksecure-cli-vm)
  

  48. [kicksecure-default-applications-cli](#kicksecure-default-applications-cli)
  

  49. [kicksecure-dependencies-cli](#kicksecure-dependencies-cli)
  

  50. [kicksecure-dependencies-system](#kicksecure-dependencies-system)
  

  51. [kicksecure-desktop-applications-recommended](#kicksecure-desktop-applications-recommended)
  

  52. [kicksecure-desktop-applications-xfce](#kicksecure-desktop-applications-xfce)
  

  53. [kicksecure-desktop-environment-essential-gui](#kicksecure-desktop-environment-essential-gui)
  

  54. [kicksecure-desktop-environment-essential-xfce](#kicksecure-desktop-environment-essential-xfce)
  

  55. [kicksecure-network-conf](#kicksecure-network-conf)
  

  56. [kicksecure-network-conf-gui](#kicksecure-network-conf-gui)
  

  57. [kicksecure-packages-dependencies-pre](#kicksecure-packages-dependencies-pre)
  

  58. [kicksecure-qubes-cli](#kicksecure-qubes-cli)
  

  59. [kicksecure-qubes-gui](#kicksecure-qubes-gui)
  

  60. [kicksecure-recommended-cli](#kicksecure-recommended-cli)
  

  61. [kicksecure-shared-host-xfce](#kicksecure-shared-host-xfce)
  

  62. [kicksecure-welcome-page](#kicksecure-welcome-page)
  

  63. [kicksecure-xfce](#kicksecure-xfce)
  

  64. [kicksecure-xfce-host](#kicksecure-xfce-host)
  

  65. [kicksecure-xfce-vm](#kicksecure-xfce-vm)
  

  66. [legacy-dist](#legacy-dist)
  

  67. [libvirt-dist](#libvirt-dist)
  

  68. [live-config-dist](#live-config-dist)
  

  69. [lkrg](#lkrg)
  

  70. [lkrg-dkms](#lkrg-dkms)
  

  71. [lkrg-systemd](#lkrg-systemd)
  

  72. [mediawiki-shell](#mediawiki-shell)
  

  73. [msgcollector](#msgcollector)
  

  74. [msgcollector-gui](#msgcollector-gui)
  

  75. [non-qubes-audio](#non-qubes-audio)
  

  76. [non-qubes-vm-enhancements-cli](#non-qubes-vm-enhancements-cli)
  

  77. [non-qubes-vm-enhancements-gui](#non-qubes-vm-enhancements-gui)
  

  78. [non-qubes-whonix-gateway-cli](#non-qubes-whonix-gateway-cli)
  

  79. [non-qubes-whonix-gateway-xfce](#non-qubes-whonix-gateway-xfce)
  

  80. [non-qubes-whonix-workstation-cli](#non-qubes-whonix-workstation-cli)
  

  81. [non-qubes-whonix-workstation-xfce](#non-qubes-whonix-workstation-xfce)
  

  82. [onion-grater](#onion-grater)
  

  83. [open-link-confirmation](#open-link-confirmation)
  

  84. [orca-screen-reader-support](#orca-screen-reader-support)
  

  85. [qubes-whonix](#qubes-whonix)
  

  86. [qubes-whonix-gateway](#qubes-whonix-gateway)
  

  87. [qubes-whonix-gateway-packages-recommended](#qubes-whonix-gateway-packages-recommended)
  

  88. [qubes-whonix-shared-packages-recommended](#qubes-whonix-shared-packages-recommended)
  

  89. [qubes-whonix-workstation](#qubes-whonix-workstation)
  

  90. [qubes-whonix-workstation-packages-recommended](#qubes-whonix-workstation-packages-recommended)
  

  91. [rads](#rads)
  

  92. [ram-wipe](#ram-wipe)
  

  93. [repository-dist](#repository-dist)
  

  94. [repository-dist-wizard](#repository-dist-wizard)
  

  95. [ro-mode-init](#ro-mode-init)
  

  96. [sandbox-app-launcher](#sandbox-app-launcher)
  

  97. [sdwdate](#sdwdate)
  

  98. [sdwdate-gui](#sdwdate-gui)
  

  99. [security-misc](#security-misc)
  

  100. [serial-console-enable](#serial-console-enable)
  

  101. [setup-dist](#setup-dist)
  

  102. [setup-wizard-dist](#setup-wizard-dist)
  

  103. [swap-file-creator](#swap-file-creator)
  

  104. [systemcheck](#systemcheck)
  

  105. [tb-default-browser](#tb-default-browser)
  

  106. [tb-starter](#tb-starter)
  

  107. [tb-updater](#tb-updater)
  

  108. [timesanitycheck](#timesanitycheck)
  

  109. [tor-control-panel](#tor-control-panel)
  

  110. [tor-ctrl](#tor-ctrl)
  

  111. [tor-geoipdb](#tor-geoipdb)
  

  112. [usability-misc](#usability-misc)
  

  113. [uwt](#uwt)
  

  114. [vm-config-dist](#vm-config-dist)
  

  115. [whonix-base-files](#whonix-base-files)
  

  116. [whonix-firewall](#whonix-firewall)
  

  117. [whonix-gateway-default-applications-gui](#whonix-gateway-default-applications-gui)
  

  118. [whonix-gateway-packages-dependencies-cli](#whonix-gateway-packages-dependencies-cli)
  

  119. [whonix-gateway-packages-dependencies-pre](#whonix-gateway-packages-dependencies-pre)
  

  120. [whonix-gateway-rpi](#whonix-gateway-rpi)
  

  121. [whonix-gateway-shared-packages-shared-meta](#whonix-gateway-shared-packages-shared-meta)
  

  122. [whonix-gw-network-conf](#whonix-gw-network-conf)
  

  123. [whonix-host-xfce-kvm-freedom](#whonix-host-xfce-kvm-freedom)
  

  124. [whonix-shared-default-applications-gui](#whonix-shared-default-applications-gui)
  

  125. [whonix-shared-packages-dependencies-cli](#whonix-shared-packages-dependencies-cli)
  

  126. [whonix-shared-packages-recommended-cli](#whonix-shared-packages-recommended-cli)
  

  127. [whonix-welcome-page](#whonix-welcome-page)
  

  128. [whonix-workstation-packages-dependencies-cli](#whonix-workstation-packages-dependencies-cli)
  

  129. [whonix-workstation-packages-dependencies-pre](#whonix-workstation-packages-dependencies-pre)
  

  130. [whonix-workstation-packages-recommended-cli](#whonix-workstation-packages-recommended-cli)
  

  131. [whonix-workstation-packages-recommended-gui](#whonix-workstation-packages-recommended-gui)
  

  132. [whonix-workstation-shared-packages-shared-meta](#whonix-workstation-shared-packages-shared-meta)
  

  133. [whonix-ws-network-conf](#whonix-ws-network-conf)
  



## anon-apps-config

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



## anon-apt-sources-list

**Package:** anon-apt-sources-list

**Version:** 3:5.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  31

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-apt-sources-list](https://github.com/Whonix/anon-apt-sources-list)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-apt-sources-list/anon-apt-sources-list_5.3-1_all.deb

**Size:**  31

**Sha256:**  6807b39548d4f9ad182f1832a3c98c4b9e72776d8d1d03f68aa0e97931a1dd8a

**Sha1:**  acae240132a602f4994ca9a4347bc47b1d191b96

**Md5sum:**  07f8004d4d9dc24bdb671087071d7f6c

**Description:** APT Sources List for Security-Focussed Linux Distributions
 A question of distribution maintenance strategies. The more standard
 way would indeed be populating /etc/apt/sources.list at install or build time
 and leaving /etc/apt/sources.list.d alone. The idea of managing
 /etc/apt/sources.list.d/debian.list for the user is, the security-focused
 distribution maintainers can decide when it is a better "change stable to
 oldstable", "keep wheezy as long as needed to work out [eventual!] issues
 that would break during upgrade to jessie" and such.



## anon-connection-wizard

**Package:** anon-connection-wizard

**Version:** 1:6.8-1

**Architecture:**  all

**Maintainer:**  iry <iry@riseup.net>

**Installed_size:**  216

**Recommends:**  tor, obfs4proxy

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Anon_Connection_Wizard](https://www.whonix.org/wiki/Anon_Connection_Wizard)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-connection-wizard/anon-connection-wizard_6.8-1_all.deb

**Size:**  216

**Sha256:**  447f2fbdc58835e70f54843f1b7077eff914b0838946ca4533b30dbd971b79d0

**Sha1:**  3a05c0451146603b8ac22119798a8384ed223823

**Md5sum:**  f8e83d977c6b32b5f698db289484743e

**Description:** Tor Connection Configuration (ACW)
 WARNING: Not (yet) a standalone ready to use outside of Whonix:
 .
 Creates a Tor settings file:
 `/usr/local/etc/torrc.d/40_tor_control_panel.conf`
 .
 anon-connection-wizard (ACW) is a Tor-launcher-like application that helps
 users in different Internet environment connect to the Tor network.
 It helps user to configure Tor to use a proxy and/or Tor bridges.
 This application is especially useful for system Tor users who would like
 to run the standalone core Tor with different torified applications.
 The wizard can be run at any time to change the connection configuration.
 .
 Creates a Tor settings file:
 `/usr/local/etc/torrc.d/40_tor_control_panel.conf`
 .
 anon-connection-wizard is produced independently from the Tor anonymity
 software and carries no guarantee from The Tor Project about quality,
 suitability or anything else.



## anon-gw-anonymizer-config

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



## anon-gw-base-files

**Package:** anon-gw-base-files

**Version:** 3:4.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  49

**Recommends:**  

**Conficts:**  anon-ws-base-files, diverts-etc++skel++.config++xfce4++xfconf++xfce-perchannel-xml++xfce4-desktop.xml

**Replaces:**  

**Provides:**  diverts-etc++skel++.config++xfce4++xfconf++xfce-perchannel-xml++xfce4-desktop.xml

**Homepage:**  [https://github.com/Whonix/anon-gw-base-files](https://github.com/Whonix/anon-gw-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-gw-base-files/anon-gw-base-files_4.2-1_all.deb

**Size:**  49

**Sha256:**  2634322e2d86baa1ac1e708a5a1d60f02856879559461f0fd892f6b856ade86a

**Sha1:**  129655d5c4063813ed44d4682424455fa260407f

**Md5sum:**  61d5a1cf39a5cec6895c395aac699f6c

**Description:** Base files for Anonymity Distribution Gateways
 Provides a /usr/share/anon-gw-base-files/gateway marker file, which allows
 other packages to identify, that this is an anonymity distribution gateway.
 .
 Whonix-Gateway grub branding, motd and issue banner.
 .
 Sets Xfce desktop and display setting, wallpaper and desktop icons.
 /etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-desktop.xml.anondist
 .
 Do not remove, unless you no longer wish to use an anonymity distribution
 gateway.



## anon-shared-build-apt-sources-tpo

**Package:** anon-shared-build-apt-sources-tpo

**Version:** 3:5.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  89

**Recommends:**  deb.torproject.org-keyring

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-shared-build-apt-sources-tpo](https://github.com/Whonix/anon-shared-build-apt-sources-tpo)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-shared-build-apt-sources-tpo/anon-shared-build-apt-sources-tpo_5.5-1_all.deb

**Size:**  89

**Sha256:**  95dd8147434d1e485d527a9a6bd5dbed703438747613bc6b4d280a91f411421b

**Sha1:**  e35b6068e7f26c2bb1c9b15a6720d7f358d14c85

**Md5sum:**  b05d33b40ed145e7093a6800f2fcd04a

**Description:** Adds TPO's APT repository to Derivative Linux Distributions
 Comes with "deb http://deb.torproject.org/torproject.org stable main", The Tor
 Project's APT signing key.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## anon-ws-base-files

**Package:** anon-ws-base-files

**Version:** 3:4.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  60

**Recommends:**  

**Conficts:**  anon-gw-base-files, diverts-etc++skel++.config++xfce4++xfconf++xfce-perchannel-xml++xfce4-desktop.xml

**Replaces:**  whonix-ws-start-menu-additions

**Provides:**  diverts-etc++skel++.config++xfce4++xfconf++xfce-perchannel-xml++xfce4-desktop.xml

**Homepage:**  [https://github.com/Whonix/anon-ws-base-files](https://github.com/Whonix/anon-ws-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-ws-base-files/anon-ws-base-files_4.2-1_all.deb

**Size:**  60

**Sha256:**  f1519dae727f52b08bf91f06ad70ebe6fa59598a62912db5280d0a9a6ba3a4f7

**Sha1:**  4b3b5dd9fe16043a0cfbff613f42bc2679c7bd5d

**Md5sum:**  c088f74e1ad7ac4c7b6e57569946db8e

**Description:** Base Files for Anonymity Distribution Workstations
 Contains a marker file /usr/share/anon-ws-base-files/workstation that allows
 other applications to identify, that they are running inside an Anonymity
 Distribution Workstation.
 .
 Whonix-Workstation grub branding, motd and issue banner.
 .
 Sets Xfce desktop and display setting, wallpaper and desktop icons.
 /etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-desktop.xml.anondist
 .
 Extra Start Menu Entries for Whonix-Workstation
 Contains start menu entries for the following links:
  - contribute
  - donate
  - forum
  - mailinglist
  - documentation
  - featureblog
  - importantblog
 .
 Do not remove, unless you no longer wish to use an Anonymity Distribution
 Workstation.



## anon-ws-disable-stacked-tor

**Package:** anon-ws-disable-stacked-tor

**Version:** 3:7.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  155

**Recommends:**  

**Conficts:**  diverts-etc++default++tor, diverts-usr++bin++tor, diverts-usr++sbin++tor

**Replaces:**  

**Provides:**  diverts-etc++default++tor, diverts-usr++bin++tor, diverts-usr++sbin++tor, obfs4proxy, obfsproxy, tor

**Homepage:**  [https://github.com/Whonix/anon-ws-disable-stacked-tor](https://github.com/Whonix/anon-ws-disable-stacked-tor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/anon-ws-disable-stacked-tor/anon-ws-disable-stacked-tor_7.1-1_all.deb

**Size:**  155

**Sha256:**  76168e78fec5189a77c0ca255f67ffd8eb748c6342865bb5ed38c0430b6bbf5d

**Sha1:**  5f2742d8adc7ee7349589ef67315790d15829dfd

**Md5sum:**  fc1297e186975e61ffb75c3c69a94db0

**Description:** Prevents Tor over Tor in Anonymity Distribution Workstations
 Supposed to be installed on Workstations, which prevents installing the real
 Tor package from upstream (ex: Debian, The Tor Project) APT repositories. Its
 purpose is to prevent, running Tor over Tor.
 .
 It allows installation of packages, which depend on Tor, such as TorChat,
 parcimonie and torbrowser-launcher.
 .
 This package uses the "Provides: tor" field[1], which should avoid any kinds of
 conflicts, in case upstream releases a higher version of Tor. This won't work
 for packages, which depend on an explicit version of Tor (such as TorChat).
 This is non-ideal, since for example the torchat package will install Tor, but
 still acceptable, because of the following additional implementations.
 .
 Binaries eventually installed (by the tor Debian package) /usr/bin/tor as well
 as /usr/sbin/tor are replaced with a dummy wrapper that does nothing
 (dpkg-diverted using config-package-dev).
 .
 systemd-socket-proxyd listens on Tor's default ports. system Tor's
 127.0.0.1:9050, 127.0.0.1:9051 and TBB's 127.0.0.1:9150, 127.0.0.1:9051,
 which prevents the
 default Tor Browser Bundle or Tor package by The Tor Project from opening
 these default ports, which will result in Tor failing to open its listening
 port and therefore exiting, thus preventing Tor over Tor.
 .
 See also:
 .
 * https://www.whonix.org/wiki/Dev/anon-ws-disable-stacked-tor
 * https://tor.stackexchange.com/questions/427/is-running-tor-over-tor-dangerous
 .
 [1] See "7.5 Virtual packages - Provides" on
 http://www.debian.org/doc/debian-policy/ch-relationships.html
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## apparmor-profile-dist

**Package:** apparmor-profile-dist

**Version:** 3:7.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  71

**Recommends:**  

**Conficts:**  diverts-etc++apparmor.d++abstractions++base

**Replaces:**  apparmor-profile-anondist

**Provides:**  diverts-etc++apparmor.d++abstractions++base

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-dist/apparmor-profile-dist_7.8-1_all.deb

**Size:**  71

**Sha256:**  49e104b90b5f9b1856b1de2313bc5ca9de193e09e2feaba31453168553f88a6a

**Sha1:**  0c6c349e6b66c02e2d717df36a2b4c1e168a92b1

**Md5sum:**  b7db9d047b9aad8bb9aa4f57e434248a

**Description:** AppArmor Profile for Anonymity Linux Distributions
 Displaces /etc/apparmor.d/abstractions/base with a version, that includes
 additions required for Anonymity Linux Distributions.
 .
 Does not depend on AppArmor, so this package can be installed by default on
 any anonymity distribution by default, without requiring to also have AppArmor
 installed. Just for the case, AppArmor gets installed later by the user.



## apparmor-profile-everything

**Package:** apparmor-profile-everything

**Version:** 3:7.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  165

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-everything/apparmor-profile-everything_7.4-1_all.deb

**Size:**  165

**Sha256:**  071e42873c1d9382be3c7358d3a3f67c0fc38518380a4a6b347eb429b66e90e1

**Sha1:**  086166883ad4be8af276897165333f33741b0968

**Md5sum:**  6f3a7bfb3ccd7062c27eea0744903607

**Description:** Full system AppArmor policy
 This is an AppArmor policy to confine all user space processes on the system which
 allows one to enforce a strong security model and follow principle of least privilege.
 An AppArmor policy for the init, systemd is loaded in the initramfs which then
 applies to all other processes. Specific policies for many system services/applications
 are also enforced.
 .
 This follows design ideas already present in other operating systems such as Android
 and attempts to make something similar available on desktop Linux.
 .
 In addition to locking down user space, this also protects the kernel as it restricts
 access to kernel interfaces like `/proc` or `/sys`, making kernel pointer and other
 leaks much less likely.
 .
 This does not and cannot confine the kernel or initramfs.
 .
 This is expected to be used in combination with other security technologies such as
 a hardened kernel, strong sandboxing architecture, verified boot and so on.
 .
 apparmor-profile-everything supports different boot modes: aadebug and superroot.
 aadebug allows certain permissions necessary for advanced debugging and superroot
 relaxes the policy substantially, even making bypasses possible. It is highly
 recommended to stick to the default boot mode.
 .
 It also contains a wrapper to restrict apt as apt requires permissions that may
 be abused to circumvent the policy. When updating or installing applications, you
 must use the `rapt` command.
 .
 This is still in development and breakage is likely. This should only be used by
 developers for now.
 .
 For now, please only use this development discussion forum thread:
 https://forums.whonix.org/t/apparmor-for-complete-system-including-init-pid1-systemd-everything-full-system-mac-policy/8339
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## apparmor-profile-hexchat

**Package:** apparmor-profile-hexchat

**Version:** 3:4.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  28

**Recommends:**  

**Conficts:**  

**Replaces:**  apparmor-profile-xchat

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-hexchat/apparmor-profile-hexchat_4.4-1_all.deb

**Size:**  28

**Sha256:**  28d15928e52f541fc006e3551360649d97b5028006ad00b16162d5d51112c6f2

**Sha1:**  c09486f26a3bb15ab0020e14437733d64fe46bad

**Md5sum:**  87e3a0b0456d3259237acd25900f1fd9

**Description:** AppArmor profile for HexChat IRC
 An AppArmor profile to confine HexChat IRC. This profile
 is developed by the Whonix team. HexChat IRC is developed by xchat.org
 / hexchat.github.io.
 .
 For better security.



## apparmor-profile-thunderbird

**Package:** apparmor-profile-thunderbird

**Version:** 3:4.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  33

**Recommends:**  

**Conficts:**  

**Replaces:**  apparmor-profile-icedove

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-thunderbird/apparmor-profile-thunderbird_4.9-1_all.deb

**Size:**  33

**Sha256:**  0af490ae7e6670f8a58124f1dc248fb99256f3f519dd1d976980d65f591a5ea8

**Sha1:**  7aac48763a234b35db1b271d79440bc4c8ca6e20

**Md5sum:**  83cc96aeb81216658ee01005d44634c1

**Description:** AppArmor profile for Thunderbird for Debian
 An AppArmor profile to confine Thunderbird.
 .
 This profile is just an extension of the upstream AppArmor Debian profile.
 The upstream AppArmor upstream profile is the foundation.
 .
 Primarily this AppArmor profile makes Debian's AppArmor profile for
 Thunderbird compatible with Qubes Debian based VMs.
 .
 This profile is developed by the Kicksecure team.
 Thunderbird is developed by mozilla.org.



## apparmor-profile-torbrowser

**Package:** apparmor-profile-torbrowser

**Version:** 3:7.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  40

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/AppArmor](https://www.whonix.org/wiki/AppArmor)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/a/apparmor-profile-torbrowser/apparmor-profile-torbrowser_7.9-1_all.deb

**Size:**  40

**Sha256:**  1a00566903adbaf9af68adc15b4363b0d9b9bf2185466c9eabc9690f73403e94

**Sha1:**  3188fc0d395f9cb8bc9653c60637f3686865dcc6

**Md5sum:**  f3a4e636368f6bc110a2ea7eb69fb5c6

**Description:** AppArmor profile for The Tor Browser Bundle (TBB)
 An AppArmor profile to confine The Tor Browser Bundle (TBB). This profile
 is developed by the Whonix team. TBB is developed by The Tor Project.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## apparmor-profiles-kicksecure

**Package:** apparmor-profiles-kicksecure

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/apparmor-profiles-kicksecure_26.1-1_all.deb

**Size:**  66

**Sha256:**  bec99fcaef9338c1b1ba5ce6fbdbd4f6c1756f34b6955372415fbae06456d89c

**Sha1:**  216b747008794894a1102c153c402986b8656aee

**Md5sum:**  a6090a23482e8651e1480f5dd1400ca1

**Description:** AppArmor profiles developed by the Kicksecure Team
 A metapackage, which installs apparmor profiles packages from Debian:
 .
  * apparmor-profile
  * apparmor-profiles-extra
 .
 as well as installs apparmor profiles developed by the Kicksecure team:
 .
  * apparmor-profile-thunderbird
  * apparmor-profile-torbrowser
  * apparmor-profile-hexchat
 .
 Increases security.
 .
 Safe to remove, if you know what you are doing.



## binaries-freedom

**Package:** binaries-freedom

**Version:** 0:2.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  30

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/binaries-freedom](https://github.com/Whonix/binaries-freedom)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/b/binaries-freedom/binaries-freedom_2.2-1_all.deb

**Size:**  30

**Sha256:**  e8e692545d12369f6c61717600aaea92630641eae2e10bf311cd42616b6d5a57

**Sha1:**  b22e31adf44fb0af93acdb8f44830cad271d15ee

**Md5sum:**  e5cdec5de21497fe4ca39b72623363a1

**Description:** Freedom Software Binaries
 This is an empty package at this time.
 .
 https://forums.whonix.org/t/policy-for-inclusion-of-compiled-software/6635



## bindp

**Package:** bindp

**Version:** 3:2.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  30

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/bindp](https://github.com/Whonix/bindp)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/b/bindp/bindp_2.8-1_all.deb

**Size:**  30

**Sha256:**  1d18bc1e72438fdd9a89a157c0397cb9bd7ea68f54c1e80f00b389eaa18defff

**Sha1:**  447b839b3dab809c43d8747bcddba7eb92e6d531

**Md5sum:**  a79f7da4039effaf769417b296451a7c

**Description:** Binding specific IP and Port for Linux Running Application
 This package is probably most useful for Anonymity Distributions.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## bootclockrandomization

**Package:** bootclockrandomization

**Version:** 3:5.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  56

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Dev/TimeSync](https://www.whonix.org/wiki/Dev/TimeSync)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/b/bootclockrandomization/bootclockrandomization_5.5-1_all.deb

**Size:**  56

**Sha256:**  c7e0ac085e502331a83a531756e6c0b9221e8fa2513feb1923b105020bd5660a

**Sha1:**  15baf9d40e3e1cd01493355fabf3fe9fd588eb7c

**Md5sum:**  f60abf26052ce5e3fcbe2e4dbe78d159

**Description:** Randomizes clock when systems boots
 Randomizes clock at boot time. Moves clock a few seconds and nanoseconds
 to past or future. Useful in context of anonymity/privacy/Tor.
 .
 This is useful to enforce the design goal, that the host clock and
 Gateway/Workstation clock should always slightly differ (even before secure
 timesync succeeded!) to prevent time based fingerprinting / linkablity
 issues.
 .
 Runs before Tor / sdwdate (if installed).
 .
 See also: https://www.whonix.org/wiki/Dev/TimeSync



## corridor

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



## damngpl

**Package:** damngpl

**Version:** 3:3.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  33

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [http://www.finnie.org/software/damngpl/damngpl](http://www.finnie.org/software/damngpl/damngpl)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/damngpl/damngpl_3.3-1_all.deb

**Size:**  33

**Sha256:**  63fd09ee3a44126cd574b5757187d9f45537bddde93f8544d1bb38458dad456b

**Sha1:**  873db01552c2045c088b2a394946ce8907517618

**Md5sum:**  f5c5d3f54c4fe15ab667b408d257da1b

**Description:** Extract source package info from Debian status files
 damngpl will parse a Debian-style /var/lib/dpkg/status file and extract source
 package information about installed packages. This information can be used in
 several ways, usually to download source packages.
 .
 Multiple input files can be specified on the command line, or piped into
 standard input if no files are specified. Results are returned to standard
 output.
 .
 The name damngpl was chosen as a tongue-in-cheek description of its purpose
 (downloading Debian sources for the Finnix project to remain GPL compliant).
 Please do not send hate mail to the author, thinking he is anti-GPL. He's not.
 .
 See also:
 http://blog.finnix.org/2011/08/21/finnix-and-gpl-compliance/



## deb.torproject.org-keyring

**Package:** deb.torproject.org-keyring

**Version:** 2022.04.27.1

**Architecture:**  all

**Maintainer:**  Peter Palfrader <weasel@debian.org>

**Installed_size:**  20

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  []()

**Priority:**  important

**Section:** misc

**Filename:**  pool/main/d/deb.torproject.org-keyring/deb.torproject.org-keyring_2022.04.27.1_all.deb

**Size:**  20

**Sha256:**  806f1d6eae45e2ea50c21342feeacbdd84acbb28b876ea7154671f1c643718a2

**Sha1:**  6cd7b7032da955f5c0a216af0db9db97696732d1

**Md5sum:**  a65ae8bbbed72ca2b2f50d5466ef8803

**Description:** GnuPG archive key of the deb.torproject.org repository
 The deb.torproject.org repository digitally signs its Release
 files. This package contains the current repository key used for
 that, and upon installation configures your system to accept archives
 signed with this key.



## debug-misc

**Package:** debug-misc

**Version:** 3:2.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  71

**Recommends:**  

**Conficts:**  

**Replaces:**  grub-output-verbose

**Provides:**  

**Homepage:**  [https://github.com/Whonix/debug-misc](https://github.com/Whonix/debug-misc)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/debug-misc/debug-misc_2.8-1_all.deb

**Size:**  71

**Sha256:**  734405700ec2c1e9a644c3b012d4fd9e7f748c95c6a5747b4545ec63a28f10bf

**Sha1:**  03e5abd8b2ea2964729cfc1cea622a22224df609

**Md5sum:**  c2326a39590fd23100f9e24698f99bcf

**Description:** Enables miscellaneous debug settings
 Ships a `/etc/default/grub.d/45_debug-misc.cfg` configuration file,
 that removes `quiet`, `loglevel=0` and `debugfs=off` from the
 `GRUB_CMDLINE_LINUX_DEFAULT` variable and adds `debug=vc` to the kernel
 boot parameter to enable verbose output during the initial ramdisk boot
 phase.
 .
 Undo debugging related `sysctl` settings by package `security-misc`.
 .
 Enables persistent systemd journal log.
 .
 Disables `/lib/systemd/coredump.conf.d/disable-coredumps.conf` by package
 `security-misc` by creating a symlink from
 `/etc/systemd/coredump.conf.d/disable-coredumps.conf` to `/dev/null`.
 `debian/debug-misc.links`
 .
 Disables `panic-on-oops`, `remove-system.map` by package `security-misc`.
 .
 `config-package-dev` `hide` `/etc/sysctl.d/30_silent-kernel-printk.conf` which
 kernel.printk to default as if security-misc would not have lowered verbosity.
 .
 Configure systemd `getty` service to not clear `tty`.
 `/lib/systemd/system/getty@tty.service.d/30_debug-misc.conf`
 .
 Coredumps are enabled.
 `/etc/security/limits.d/40_debug-misc.conf`
 .
 Coredumps may contain important information such as encryption keys or
 passwords. Package `security-misc` disables coredumps. Package `debug-misc`
 re-enables coredumps.
 .
 Contains a helper tool to cause a segfault for testing purposes.
 `segfault-build` creates `segfault-run`. Running `segfault-run` results in
 `segfault-run` terminating with a segfault. This is useful to test if
 coredump files are being generated when an application crashes.
 `/usr/sbin/segfault-build`
 `/usr/share/debug-misc/segfault.c`
 .
 For better usability, to ease debugging in case of issues.
 .
 For better security, this package should only be installed on specific
 machines that require debugging. Unfortunately, security and debugging are
 conflicting optimization goals.



## desktop-config-dist

**Package:** desktop-config-dist

**Version:** 3:7.0-1

**Architecture:**  all

**Maintainer:**  Algernon <33966997+Algernon-01@users.noreply.github.com>

**Installed_size:**  96

**Recommends:**  

**Conficts:**  

**Replaces:**  whonix-xfce-desktop-config

**Provides:**  whonix-xfce-desktop-config

**Homepage:**  [https://github.com/Kicksecure/desktop-config-dist](https://github.com/Kicksecure/desktop-config-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/desktop-config-dist/desktop-config-dist_7.0-1_all.deb

**Size:**  96

**Sha256:**  90425f1e6566095b3d3b02f72d25e6b3d7104dbe757ac4c3c8fd0cfe66631fde

**Sha1:**  75e3b5469e1c1ed5a9c7ec3d8203f8e28e0ffb33

**Md5sum:**  c7485f2ddec64af48f001563faf933f9

**Description:** Configuration for Derivative Desktop
 Sets desktop and display setting, wallpaper and desktop icons.
 Sets icon theme and style.
 Settings for the default panel aka task bar, like panel position/color/size
 and panel plugins/shortcuts.
 .
 Autologin for user 'user' setting in lightdm.
 .
 Live check systray indicator which indicates the status of grub-live, whether
 the system was booted into persistent or live mode. See also:
 https://www.kicksecure.com/wiki/grub-live
 .
 Adds start menu entries for web browser, terminal emulator, file manager.
 .
 Sets Whisker Menu for better usability.
 .
 Disable maximize windows when moving to top for better privacy.
 .
 Disables thumbnails for better security.
 .
 Disables save on exit for better privacy.
 .
 Ships `zsh` derivative configuration settings folder `/etc/zsh`.
 But does not configure `zsh` as default shell.
 (That is up to package `dist-base-files`.)



## desktop-config-dist-dependencies

**Package:** desktop-config-dist-dependencies

**Version:** 3:7.0-1

**Architecture:**  all

**Maintainer:**  Algernon <33966997+Algernon-01@users.noreply.github.com>

**Installed_size:**  25

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/desktop-config-dist](https://github.com/Kicksecure/desktop-config-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/desktop-config-dist/desktop-config-dist-dependencies_7.0-1_all.deb

**Size:**  25

**Sha256:**  be3d476dda80bd0babc4b0710ccf6e8e9ed2fe3e5ca413897b1fa50eba05ba49

**Sha1:**  35e2e962bf851aeccfd5eb0bf88c19815cc9ff96

**Md5sum:**  8d862a0376da5c07c1036c92f519c300

**Description:** Dependencies of desktop-config-dist
 A metapackage with dependencies for package desktop-config-dist.
 .
 Only useful for Non-Qubes. Not useful in Qubes.



## developer-meta-files

**Package:** developer-meta-files

**Version:** 3:23.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  226

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/developer-meta-files](https://github.com/Kicksecure/developer-meta-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/developer-meta-files/developer-meta-files_23.3-1_all.deb

**Size:**  226

**Sha256:**  2c5222e0fc0cb990df011cf5dd9844b184e13ce9b3e0c8284a23131b1bdf61ac

**Sha1:**  7043f98547e7479c0777654601b889525b10f6b1

**Md5sum:**  f8a240f817a1003a532971d600e9c871

**Description:** Linux Distributions Maintenance Helper Scripts
 Todo
 .
 Description



## dist-base-files

**Package:** dist-base-files

**Version:** 3:8.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  78

**Recommends:**  

**Conficts:**  anon-base-files

**Replaces:**  anon-base-files

**Provides:**  anon-base-files

**Homepage:**  [https://github.com/Whonix/dist-base-files](https://github.com/Whonix/dist-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/d/dist-base-files/dist-base-files_8.8-1_all.deb

**Size:**  78

**Sha256:**  7ef2a56cfc7cd1f0ea3c65091f162299ba64752786921ac21caec0005002e3f6

**Sha1:**  c4f5b522b61a8cbe931107a771e13aae3d111fbc

**Md5sum:**  90b3a0348633b76ee713be54c96f64dc

**Description:** base files for distributions
 Creates user `user` with password `changeme` (not in Qubes).
 That is if user `user` is not existing yet.
 And if it does create user `user` it also locks the root account.
 Therefore root account locking effectively only happens in new
 builds not having user `user` already created.
 .
 Adds user `user` to groups `cdrom`, `audio`, `dip`, `sudo`, `plugdev`.
 .
 Ships a systemd unit file dist-skel-first-boot.service
 which runs `/usr/libexec/helper-scripts/first-boot-skel`
 (part of helper-scripts) package.
 .
 Simplifies sudo default lecture to only showing the default password once.
 .
 Creates version file `/var/lib/dist-base-files/build_version`.
 .
 Default shell: Sets default shell for user `user` to `zsh`.
 (Unless file `/etc/no-shell-change` exists.)
 `debian/dist-base-files.postinst`
 .
 This package gets installed by default in both, Kicksecure and Whonix.



## dummy-dependency

**Package:** dummy-dependency

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  firefox-esr, qubes-core-agent-passwordless-root, tb-default-browser, tb-starter, tb-updater

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency_26.1-1_all.deb

**Size:**  66

**Sha256:**  1ef8ad907d255c0da30bc6a12969087f95928b5cd735978dcb3ac1483302bc81

**Sha1:**  eae17e8567907bc2c6f3d400c75e669824cd34a2

**Md5sum:**  e345bf79c7453e8f3ba963c423d9e159

**Description:** dummy package to satisfy architecture specific dependencies
 A metapackage, which satisfies the dependency on:
 .
  - tb-updater
  - tb-starter
  - tb-default-browser
  - qubes-core-agent-passwordless-root
  - firefox-esr
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-apparmor-profiles-kicksecure

**Package:** dummy-dependency-apparmor-profiles-kicksecure

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  apparmor-profiles-kicksecure

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-apparmor-profiles-kicksecure_26.1-1_all.deb

**Size:**  66

**Sha256:**  0f30c8313a960143c1ad86ff63cc1c55ce4a4d071c6c1dd5ddfd895b48afe5ef

**Sha1:**  db240ca14a665e5f9a448bc8e0e19e76e651d0fd

**Md5sum:**  1fa2b9da9ead6e089d3ad6d9bf866843

**Description:** dummy package apparmor-profiles-kicksecure
 A metapackage, which satisfies the dependency on apparmor-profiles-kicksecure.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-bindp

**Package:** dummy-dependency-bindp

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  bindp

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-bindp_26.1-1_all.deb

**Size:**  66

**Sha256:**  35933e68aed21916e1c8e768b66f65a3cb0917accb1537f8c20a4d8cfdd93d2b

**Sha1:**  d32f6d4c9096707f3d654f393177eee4123cf173

**Md5sum:**  c38be564509197d3a59dfefb7307f0e6

**Description:** dummy package to satisfy architecture specific dependency bindp
 A metapackage, which satisfies the dependency on bindp.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-electrum

**Package:** dummy-dependency-electrum

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  dummy-dependency-hardened-electrum

**Provides:**  dummy-dependency-hardened-electrum, electrum

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-electrum_26.1-1_all.deb

**Size:**  66

**Sha256:**  5b95ca103f1c09df55eca9f8f6d6f6a856ffc2dd26b4f50768d72af594fab976

**Sha1:**  0075d7c4351e067e18a809f9de39a453c200ec79

**Md5sum:**  9a36b328b3a885191a2205549091249c

**Description:** dummy package to satisfy architecture specific dependency electrum
 A metapackage, which satisfies the dependency on electrum.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-hardened-electrum

**Package:** dummy-dependency-hardened-electrum

**Version:** 3:24.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  64

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  electrum

**Homepage:**  [https://github.com/Whonix/kicksecure-meta-packages](https://github.com/Whonix/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-hardened-electrum_24.8-1_all.deb

**Size:**  64

**Sha256:**  96eaa6f25e74cb9581afc4cff277d7e4a86d1df2c36390b6db507dd80c254db0

**Sha1:**  0fc24bf80ed04ab7cd26143c77389d90c51b5909

**Md5sum:**  b27676cd68e96d5cd80089ff965f47a7

**Description:** dummy package to satisfy architecture specific dependency electrum
 A metapackage, which satisfies the dependency on electrum.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-hardened-malloc

**Package:** dummy-dependency-hardened-malloc

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  hardened-malloc

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-hardened-malloc_26.1-1_all.deb

**Size:**  66

**Sha256:**  99a1721fca991a70d8f49b56e9022bfd19cbb2d0e3cbee29f93597cfcd81b3a8

**Sha1:**  1f7cd3019ea13a14146512edca0a1ced0f06ce2f

**Md5sum:**  eef93800539e552750347f02e3bf3585

**Description:** dummy package to satisfy architecture specific dependency hardened-malloc
 A metapackage, which satisfies the dependency on:
 .
 hardened-malloc
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-kloak

**Package:** dummy-dependency-kloak

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  kloak

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-kloak_26.1-1_all.deb

**Size:**  66

**Sha256:**  9b271c898b67df7bd45e25fbd0b7579670e7cb9ee36cada25bc86e44cab6d305

**Sha1:**  9c406606e20eef11ea1a57d6bf9721d2df83e87a

**Md5sum:**  538f8cd03135b31c9fe0106f8834b205

**Description:** dummy package to satisfy architecture specific dependency kloak
 A metapackage, which satisfies the dependency on kloak.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-tirdad

**Package:** dummy-dependency-tirdad

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  tirdad

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-tirdad_26.1-1_all.deb

**Size:**  66

**Sha256:**  2bbce1c8843191ba155e97719b857cc2328351bf78bc1fc74a22ff84960ea9cd

**Sha1:**  1a46fe4f4abc9714fd07e1e4ddc53bf49ecbc449

**Md5sum:**  7af471f96d664a15f20c75f1f823f6d7

**Description:** dummy package to satisfy architecture specific dependency tirdad
 A metapackage, which satisfies the dependency on tirdad.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## dummy-dependency-xorg-vm

**Package:** dummy-dependency-xorg-vm

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  xserver-xorg-video-vmware

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/dummy-dependency-xorg-vm_26.1-1_all.deb

**Size:**  66

**Sha256:**  6ea25b2717cfe0e086ef667cb4121a96c2d86f4df3373c7ea8ef77f7c0ca7b58

**Sha1:**  4470a87c65b513e773080873d518718acc296aa3

**Md5sum:**  0d8c6d01e56e68f5ea6ff7481c6a090e

**Description:** dummy dependency xserver-xorg-video-vmware
 A metapackage, which satisfies the dependency on xserver-xorg-video-vmware.
 .
 This package cannot provide a real implementation of that package. It is only
 a dummy to satisfy the dependency.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## genmkfile

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



## gpg-bash-lib

**Package:** gpg-bash-lib

**Version:** 3:3.6-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  615

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/gpg-bash-lib](https://github.com/Whonix/gpg-bash-lib)

**Priority:**  optional

**Section:** libs

**Filename:**  pool/main/g/gpg-bash-lib/gpg-bash-lib_3.6-1_all.deb

**Size:**  615

**Sha256:**  ba09ba586fb40a648491ddde8680c6f9836b73f6385327452181d7a5cc49c560

**Sha1:**  9e3019f34211b3baf35c6832a914c5b9c32f7470

**Md5sum:**  4884eb00590ac1e45e506be26fe114ec

**Description:** gpg bash library
 Abstracts file verification into common functions. Allows detecting of stale
 files, i.e. detection downgrade or indefinite freeze attacks by implementing
 a valid-until like mechanism.
 .
 Internally parses gpg's --status-file output.
 .
 For better security.



## grub-live

**Package:** grub-live

**Version:** 3:3.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  26

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  boot-live, grub-live-boot

**Homepage:**  [https://github.com/Whonix/grub-live](https://github.com/Whonix/grub-live)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/g/grub-live/grub-live_3.7-1_all.deb

**Size:**  26

**Sha256:**  4cdca9475a74858073f971541e0f1c46645d439595a58c0094374f088355f037

**Sha1:**  8473b4c5cba3c67565c51294bb639e2192e1e063

**Md5sum:**  9baf3133f2ad134e7955d6337176397c

**Description:** grub live boot menu entry
 Allows booting the system in live mode. Meaning, no persistent modifications
 will be written to the disk. All changes stay in RAM.
 .
 Adds a grub live boot menu entry.
 .
 Existing grub boot entries stay unmodified.
 .
 No claims are made with regard to anti forensics.



## grub-live-dracut

**Package:** grub-live-dracut

**Version:** 3:3.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  18

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  boot-live, grub-live-boot

**Homepage:**  [https://github.com/Whonix/grub-live](https://github.com/Whonix/grub-live)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/g/grub-live/grub-live-dracut_3.7-1_all.deb

**Size:**  18

**Sha256:**  d01467a25bdddb2da57e5e476f512d5a7575ef8d64896733dca7aa37d08203a9

**Sha1:**  2cc59d331260e1dbe5f448561d6b6d3833ba6e6e

**Md5sum:**  da9f320fdbe69caf39b8dd91273dd0ef

**Description:** grub live dracut dependencies
 Dracut version metapackage for grub-live.
 .
 See also the package grub-live.



## grub-live-initramfs-tools

**Package:** grub-live-initramfs-tools

**Version:** 3:3.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  18

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  boot-live, grub-live-boot

**Homepage:**  [https://github.com/Whonix/grub-live](https://github.com/Whonix/grub-live)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/g/grub-live/grub-live-initramfs-tools_3.7-1_all.deb

**Size:**  18

**Sha256:**  12f201e36136dff5091491fe8f5a0c344a624e2c8fb751546c13307b52983d76

**Sha1:**  bb623fe754f05785b9ad3bae4106c33639c2d821

**Md5sum:**  04f1356f0378cf4f4370de872a2f07fb

**Description:** grub live initramfs-tools dependencies
 initramfs-tools version metapackage for grub-live
 .
 See also grub-live package.



## hardened-kernel

**Package:** hardened-kernel

**Version:** 3:4.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  442

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/hardened-kernel](https://github.com/Whonix/hardened-kernel)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/h/hardened-kernel/hardened-kernel_4.0-1_all.deb

**Size:**  442

**Sha256:**  963ed94b23fc984b0ac9b7df73add6ac9c39862dba90b3689fcefe1782b210de

**Sha1:**  f1562271f52d06110c7bd8de11e9482e28f63b65

**Md5sum:**  10824819d4e8267d8b8ea33124a8736e

**Description:** Hardened Kernel for Host and VMs
 This is a hardened kernel configuration for Whonix / Kicksecure.
 hardened-vm-kernel is designed specifically for virtual machines and
 hardened-host-kernel is designed for hosts.
 .
 Both configs try to have as many hardening options enabled as possible and
 have little attack surface. hardened-vm-kernel only has support for VMs
 and all other hardware options are disabled to reduce attack surface and
 compile time.
 .
 During installation of hardened-vm-kernel, it compiles the kernel on your own
 machine and does not use a pre-compiled kernel. This ensures the kernel
 symbols in the compiled image are completely unique which makes it far harder
 for kernel exploits. This is possible due to hardened-vm-kernel having only VM
 config options enabled which drastically reduces compile time.
 .
 During installation of hardened-host-kernel, the kernel is not compiled on
 your machine and it uses a pre-compiled kernel. This is because the host
 kernel needs most hardware options enabled to support most devices which makes
 compilation take a very long time.
 .
 The VM kernel is more secure than the host kernel due to having less attack
 surface and not being pre-compiled but if you want more security for the host,
 it is recommended to edit the hardened host config, enable only the hardware
 options you need and compile the kernel yourself. This makes the security of
 the host and VM kernel comparable.
 .
 Both configs were based on the default Debian config.
 .
 These kernels use the linux-hardened patch for further hardening. Custom
 hardening patches should be
 sent there.
 .
 This only supports LTS kernels as they have the least attack surface (stable
 kernels have more code and more bugs) and the best stability.
 .
 Build script /usr/share/hardened-vm-kernel/build does not run automatic yet.
 .
 Kernel does not get installed automatic yet.
 .
 See also development discussion:
 http://forums.whonix.org/t/kernel-recompilation-for-better-hardening



## helper-scripts

**Package:** helper-scripts

**Version:** 3:18.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  248

**Recommends:**  

**Conficts:**  

**Replaces:**  anon-shared-helper-scripts, anon-ws-leaktest, curl-scripts, python-guimessages, python3-guimessages

**Provides:**  

**Homepage:**  [https://github.com/Whonix/helper-scripts](https://github.com/Whonix/helper-scripts)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/h/helper-scripts/helper-scripts_18.9-1_all.deb

**Size:**  248

**Sha256:**  e146a0daa53c4399eb4d006cb6f6ff86ca4deb9775e022d70052ff563497e9b1

**Sha1:**  01078c3fbd10d46fb7211312a542ee9258469eb7

**Md5sum:**  111b6983dea2c4abf5bf53eb49c3cb9d

**Description:** Helper scripts useful for Linux Distributions
 Contains a script for curl progress bar in terminal. Includes another script
 to convert curl exit codes to curl status messages. Implemented in bash.
 Common code that can be used by other scripts.
 .
 Library that can be used by other (anonymity related) packages that want to
 programmatically get information about states of Tor. Common code, that is
 often required. Includes bash and Python helper scripts.
 .
 Leak Test for Anonymity Distribution Workstations
 Integrated leak test.
 Needs to be manually run.
 See: https://www.whonix.org/wiki/Dev/Leak_Tests
 .
 Translatable GUI Messages
 Generic modules guimessage.py and translations.py.
 Called with two parameters: .yaml file path and yaml section. Return
 translations according to distribution local language (Python 'locale').
 .
 Provides the ld-system-preload-disable wrapper to disable /etc/ld.so.preload
 per application via bubblewrap. Useful if hardened_malloc is being globally
 preloaded and needs to be disabled for some applications.



## icon-pack-dist

**Package:** icon-pack-dist

**Version:** 3:3.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  2633

**Recommends:**  

**Conficts:**  anon-icon-pack

**Replaces:**  anon-icon-pack

**Provides:**  anon-icon-pack

**Homepage:**  [https://github.com/Whonix/icon-pack-dist](https://github.com/Whonix/icon-pack-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/i/icon-pack-dist/icon-pack-dist_3.5-1_all.deb

**Size:**  2633

**Sha256:**  e3629a4a9aa57d3329d1bdc657942f52841e81d225b492e9131aa2c63fd07d97

**Sha1:**  0b173114c1254564f24d3a2475c22e4747beb30a

**Md5sum:**  c1d6efbed42f7db0121fc8f55028674f

**Description:** Icon Pack for Derivative Distributions
 Contains icons, that are used by other derivative distribution specific
 packages. Others are welcome to use these icons according to their Free
 licenses as well.



## initializer-dist

**Package:** initializer-dist

**Version:** 3:6.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  39

**Recommends:**  

**Conficts:**  anon-shared-build-remember-sources, anon-shared-build-sanity-checks, whonix-initializer

**Replaces:**  anon-shared-build-remember-sources, anon-shared-build-sanity-checks, whonix-initializer

**Provides:**  anon-shared-build-remember-sources, anon-shared-build-sanity-checks, whonix-initializer

**Homepage:**  [https://www.whonix.org/wiki/Verifiable_Builds](https://www.whonix.org/wiki/Verifiable_Builds)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/i/initializer-dist/initializer-dist_6.0-1_all.deb

**Size:**  39

**Sha256:**  a00bd380313f26ec293bac2594b488e5cd262f934549bf37a18d792260af504c

**Sha1:**  66f8830a00aee582e16dcafab7e78ba1f4bb41b1

**Md5sum:**  1b8440509c2c3a14e66eed39562d66d2

**Description:** Initializes Linux distributions, Release Upgrades and Legacy
 Contains a chroot-scripts-post.d script, that cleans up temporary files, logs.
 .
 Deletes random seeds. Since these should not be included in a redistributed
 image. Also sometimes called 'golden' image.
 .
  - /var/lib/urandom/random-seed
  - /var/lib/systemd/random-seed
  - /var/lib/random-seed
  - See also: https://systemd.io/RANDOM_SEEDS.html



## kicksecure-base-files

**Package:** kicksecure-base-files

**Version:** 3:6.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  115

**Recommends:**  

**Conficts:**  diverts-etc++issue, diverts-etc++motd, diverts-etc++skel++.bashrc

**Replaces:**  

**Provides:**  diverts-etc++issue, diverts-etc++motd, diverts-etc++skel++.bashrc

**Homepage:**  [https://github.com/Kicksecure/kicksecure-base-files](https://github.com/Kicksecure/kicksecure-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/k/kicksecure-base-files/kicksecure-base-files_6.4-1_all.deb

**Size:**  115

**Sha256:**  61ba743e9e2a6d26bb35c6421c1eeeddb423092913cef87888b86c96b0b488a5

**Sha1:**  b5d1e321d9df35ba9ba4943be6d5d96b8c146929

**Md5sum:**  024715aeec8812960347eb8d8bd70050

**Description:** Kicksecure base system miscellaneous files
 This package contains several important miscellaneous files, such as
 /etc/issue, /etc/motd, /etc/dpkg/origins/kicksecure,
 /etc/skel/.bashrc, /usr/bin/kicksecure, and others.
 .
 Sets the KICKSECURE environment variable to 1 as well.



## kicksecure-cli

**Package:** kicksecure-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  451e2cee5cd5a00b00a80b1daa808ee60c60cd94b4822c22b12864b85a48d8a7

**Sha1:**  c9f327b3481437827c17f8057762ff0136598080

**Md5sum:**  7736381aafa1b114b2b4a6f08e561ad3

**Description:** Kicksecure command line interface CLI
 A metapackage, which installs packages, for Kicksecure CLI.
 .
 Do not remove.



## kicksecure-cli-host

**Package:** kicksecure-cli-host

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-cli-host_26.1-1_all.deb

**Size:**  66

**Sha256:**  3fbceb91fdd2c18e67335ea04761b47df6be0cd55db456b7097402f74292da6b

**Sha1:**  2ca28459775d5450b1887d6af669996cb06629c1

**Md5sum:**  b743d701c1ab5e0cf07678b01ed844b0

**Description:** Kicksecure Host command line interface CLI
 A metapackage, which installs packages, for Kicksecure CLI Host.
 .
 Do not remove.



## kicksecure-cli-vm

**Package:** kicksecure-cli-vm

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-cli-vm_26.1-1_all.deb

**Size:**  66

**Sha256:**  63b3253aa672f9665aeb2831454367522a74291b8a57f76ba693ad14efb5d367

**Sha1:**  55dcb188138c68ea241411dc4c47374e951a6391

**Md5sum:**  6386ec1d1fc820cb8a6f69e6569c930f

**Description:** Kicksecure command line interface CLI VMs
 A metapackage, which installs packages, for Kicksecure CLI Virtual Machines.
 .
 Not suitable for Qubes since it depends on packages not yet compatible
 with Qubes.
 .
 Do not remove.



## kicksecure-default-applications-cli

**Package:** kicksecure-default-applications-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-default-applications-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  0e5598f3a202c66f290abbc10bbc2479add19a8bb21a87e4c2f70573b2f7d287

**Sha1:**  6cd8cba91894401a8a2ddcd3ceba7485f7ef66ae

**Md5sum:**  24cc95aba5c23784fe0846d8add18675

**Description:** Default applications packages for Kicksecure
 A metapackage, which includes default packages to ensure, Kicksecure
 useful recommended tools are installed.
 .
 Safe to remove, if you know what you are doing.



## kicksecure-dependencies-cli

**Package:** kicksecure-dependencies-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-dependencies-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  c3518bb0e45354bb57c71d4a07a73284c98a13000718fdcde93af0230e3f03b0

**Sha1:**  6465e076c9f01c0640c320307b6bdf53444c612b

**Md5sum:**  efe0d990cfb3876fdf64f94b35d7fb91

**Description:** Dependencies for hardened systems CLI
 A metapackage, which installs command line interface (CLI) packages which
 should be installed on hardened systems.
 .
 Do not remove.



## kicksecure-dependencies-system

**Package:** kicksecure-dependencies-system

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-dependencies-system_26.1-1_all.deb

**Size:**  66

**Sha256:**  031ede3a05f27f21b5ac65bfd5ff51b7a9fbabf782b9dac1779ca297436ec528

**Sha1:**  59aeea1e806f2237fa13a90cb033f0b21a552071

**Md5sum:**  036cea52a910ffab3e57b4436eb09f76

**Description:** System for hardened systems
 A metapackage, which installs system packages which
 should be installed on hardened systems.
 .
 Currently only depends on boot process related dependencies.
 .
 Do not remove.



## kicksecure-desktop-applications-recommended

**Package:** kicksecure-desktop-applications-recommended

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-desktop-applications-recommended_26.1-1_all.deb

**Size:**  66

**Sha256:**  8fce67dac1b8703a76b8b3ad119eecbb0f01ffd204feede51faf88f4ff3246e2

**Sha1:**  693742a92cefbf500a7b16905b82b5ddfe39930c

**Md5sum:**  3e359f2afb2aa71e56837e8a344a34c2

**Description:** Kicksecure Recommended Desktop Applications
 A metapackage, which installs recommended packages, for graphical user
 interface (GUI) Kicksecure.
 .
 Do not remove.



## kicksecure-desktop-applications-xfce

**Package:** kicksecure-desktop-applications-xfce

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-desktop-applications-xfce_26.1-1_all.deb

**Size:**  66

**Sha256:**  1ed4c309a9adc47e6278915afff81083cb1bf199d45d0009ba45462b00a49774

**Sha1:**  59dc515a6934d14549a6cc2dbfbab61d2b6af096

**Md5sum:**  b7e1ee648e0882ae2156dab0c1d901c8

**Description:** Recommended applications for hardened Xfce desktop GUI
 A metapackage, which installs minimal, yet complete enough
 to contain the very basics, Xfce applications.
 .
 Safe to remove.



## kicksecure-desktop-environment-essential-gui

**Package:** kicksecure-desktop-environment-essential-gui

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-desktop-environment-essential-gui_26.1-1_all.deb

**Size:**  66

**Sha256:**  8517a5816c29a10188d5c35a67e587e66a7c753904175cfba4216266e5c692dc

**Sha1:**  111a9a23004c1137962b35028d5808561c4d719c

**Md5sum:**  a8705dbd0f16c8e596091415d6da8daf

**Description:** Desktop Depends GUI
 A metapackage, which installs dependencies for desktop environments,
 such as KDE, GNOME, etc.
 .
 kicksecure-desktop-environment-essential-xfce depends on this package.



## kicksecure-desktop-environment-essential-xfce

**Package:** kicksecure-desktop-environment-essential-xfce

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-desktop-environment-essential-xfce_26.1-1_all.deb

**Size:**  66

**Sha256:**  76a79a8ec8f440e16daaa783a1db55b8d3ae9a49cf9028ff2efb62cf80422d77

**Sha1:**  1a05816cd440707355be2e052d0ebafc1320851c

**Md5sum:**  4faa89af2c77a3be68c853ff4fb3cf33

**Description:** Recommended applications for hardened Xfce Desktop Environment
 A metapackage, which installs minimal, yet complete enough
 to contain a very basic Xfce Desktop Environment.
 .
 Safe to remove.



## kicksecure-network-conf

**Package:** kicksecure-network-conf

**Version:** 3:5.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  44

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/kicksecure-network-conf](https://github.com/Whonix/kicksecure-network-conf)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/k/kicksecure-network-conf/kicksecure-network-conf_5.3-1_all.deb

**Size:**  44

**Sha256:**  f987cc7ea21bcae95387a30ecbe5df84437d4493a323067bb71318ee28e89aa0

**Sha1:**  2747c65098e086660139eaff66d7aaf5a0dbf6c5

**Md5sum:**  0b0d05e6135c4e4ab2560f50339ac696

**Description:** Network Configuration for Kicksecure CLI
 Disables systemd Predictable Network Interface Names.
 .
 Disables systemd-resolved during boot unless file /etc/dns-enable exists.
 .
 Disables systemd-resolved fallback DNS (which by default is set to Google).
 .
 Disables NetworkManager hostname management (useful in redistributed
 Kicksecure VMs).



## kicksecure-network-conf-gui

**Package:** kicksecure-network-conf-gui

**Version:** 3:5.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  16

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/kicksecure-network-conf](https://github.com/Whonix/kicksecure-network-conf)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/k/kicksecure-network-conf/kicksecure-network-conf-gui_5.3-1_all.deb

**Size:**  16

**Sha256:**  fe72e67570178b93a3b94a618f0c2dfee823e78f617d3642f5663a5c7863bfdf

**Sha1:**  7cc3f99863d7b0bd2876ba201aa5f2c5b895f453

**Md5sum:**  a2dcd01172346a0a3c0cc4b462484ffa

**Description:** Network Configuration for Kicksecure GUI
 A metapackage with dependencies recommended for a Kicksecure GUI for
 networking.
 .
 See also kicksecure-network-conf.



## kicksecure-packages-dependencies-pre

**Package:** kicksecure-packages-dependencies-pre

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-packages-dependencies-pre_26.1-1_all.deb

**Size:**  66

**Sha256:**  5cd2ff1c97fd0fa0b8f185c65bbea49bc87744ef07c3e0c62d472533037b903c

**Sha1:**  354c6efb41d37b553aa27f3abe5ecdc905d43b33

**Md5sum:**  8d3fa907677e60b7f0f130ac88d9e8de

**Description:** Dependencies for Kicksecure that changes network related files
 A metapackage, which installs packages which Kicksecure depends on. Can not
 be merged into another package due to conflicts with chroot build process.
 .
 Do not remove.



## kicksecure-qubes-cli

**Package:** kicksecure-qubes-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-qubes-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  9feda3bdeacacc41aa19477d3661fcf7f4240ab3cd642fedddb5b25673f08a47

**Sha1:**  3da7f7ee4b10db0e05417c7c87a567dada27123f

**Md5sum:**  706f541d97323f1e04250f78706d18ad

**Description:** Default packages for Kicksecure-Qubes CLI
 A metapackage, which installs packages, for Kicksecure on Qubes without
 recommended GUI applications.
 .
 Currently only depends on kicksecure-cli but useful for future maintenance in
 case Qubes specific changes will be required.
 .
 Do not remove.



## kicksecure-qubes-gui

**Package:** kicksecure-qubes-gui

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-qubes-gui_26.1-1_all.deb

**Size:**  66

**Sha256:**  729ecad243ab3920b3720e525a7343fee9e44cbf9c3c16a9df30e5bd8a0c36bd

**Sha1:**  ba5d41ba07e600c3ad1a805c5687f71bf5476419

**Md5sum:**  74eb4f298fec2b7c91ee5f3f47f99aeb

**Description:** Default packages for Kicksecure-Qubes GUI
 A metapackage, which installs packages, for Kicksecure on Qubes including
 recommended GUI applications.
 .
 Do not remove.



## kicksecure-recommended-cli

**Package:** kicksecure-recommended-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-recommended-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  392fddc45fa8ee38214ec1e02de0ecfded8ccb945ceb85e78357bdbda7caf7bd

**Sha1:**  ee2b998e313e3ecfb8ddc9cc4d95377f8c6cc652

**Md5sum:**  70b380204c582a4f2219b9d9454b3eb5

**Description:** Recommended packages for Kicksecure
 A metapackage, which includes recommended packages to ensure, Kicksecure
 standard tools are available.
 .
 Safe to remove, if you know what you are doing.



## kicksecure-shared-host-xfce

**Package:** kicksecure-shared-host-xfce

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-shared-host-xfce_26.1-1_all.deb

**Size:**  66

**Sha256:**  babcb3255aea24cce0bd0c7320b0197432b9da52743e8f773ed90c43c253ec4f

**Sha1:**  9ba8896f13d2244b96a9f1a90caeee9a2feac8bd

**Md5sum:**  26a84b6962d95f46b0908a4243583605

**Description:** Kicksecure Shared Host Xfce GUI
 A metapackage, which installs packages, which are recommended for
 Kicksecure Xfce Host as well as a Whonix-Host with a graphical user interface
 (GUI).
 .
 Safe to remove, if you know what you are doing.



## kicksecure-welcome-page

**Package:** kicksecure-welcome-page

**Version:** 3:5.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@kicksecure.com>

**Installed_size:**  1058

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-welcome-page](https://github.com/Kicksecure/kicksecure-welcome-page)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/k/kicksecure-welcome-page/kicksecure-welcome-page_5.4-1_all.deb

**Size:**  1058

**Sha256:**  20e803feabf99bec81de941c36a22ff65bcc13d505cc876f6499155abf0b6f33

**Sha1:**  1a1bb7d3ad6abec79948480b3906a62a19a915fa

**Md5sum:**  366e188a51ffbf728bc7df88467fca3d

**Description:** Local Browser Homepage for Kicksecure
 Kicksecure specific browser start page.
 .
 Contains Kicksecure logo and Kicksecure links.
 .
 Safe to remove, if you know what you are doing.



## kicksecure-xfce

**Package:** kicksecure-xfce

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-xfce_26.1-1_all.deb

**Size:**  66

**Sha256:**  ad1f44459a91ffacb802edd6628870c6e873af4f6e0159a6030cfad9b9b2a22f

**Sha1:**  69a736717da539e92ed3b31e29b09b17858418b2

**Md5sum:**  4099657297fbb3596e2fbf2eeb068cb3

**Description:** Kicksecure Xfce GUI
 A metapackage, which installs packages, for Kicksecure Xfce.
 .
 Do not remove.



## kicksecure-xfce-host

**Package:** kicksecure-xfce-host

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-xfce-host_26.1-1_all.deb

**Size:**  66

**Sha256:**  2afbbcae61ef95e96b458680dc0d5b5b93494c2c2cafe7c77e04395b1e07796d

**Sha1:**  a7ea470108d27e0e520c8e99fe69d50bcf2e849c

**Md5sum:**  80c00bd4808a293b25ec8fdcd7657071

**Description:** Kicksecure Host Xfce GUI
 A metapackage, which installs packages, for Kicksecure Xfce Host.
 .
 Do not remove.



## kicksecure-xfce-vm

**Package:** kicksecure-xfce-vm

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/kicksecure-xfce-vm_26.1-1_all.deb

**Size:**  66

**Sha256:**  78766fa061d280a701fc1ccbba23ea359b16692dd3705ac922c7733fa2043ce0

**Sha1:**  bfb25b1623b7752fc9a95ce34e93b292f6850dc7

**Md5sum:**  b5766e15ee7fe3023b31f97364aa84ab

**Description:** Kicksecure Xfce GUI for VMs
 A metapackage, which installs packages, for Kicksecure Xfce in Virtual
 Machines.
 .
 Not suitable for Qubes since it depends on packages not yet compatible
 with Qubes.
 .
 Do not remove.



## legacy-dist

**Package:** legacy-dist

**Version:** 3:13.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  93

**Recommends:**  

**Conficts:**  vbox-disable-timesync, whonix-legacy

**Replaces:**  vbox-disable-timesync, whonix-legacy

**Provides:**  vbox-disable-timesync, whonix-legacy

**Homepage:**  [https://github.com/Whonix/legacy-dist](https://github.com/Whonix/legacy-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/l/legacy-dist/legacy-dist_13.3-1_all.deb

**Size:**  93

**Sha256:**  e1528c42b8755ce976042eeb4847583dd73934656c4e24c44f0bfbca03b90edd

**Sha1:**  fe3e435aacc97d1aecaac1cf0ba494df94d91821

**Md5sum:**  11316d5dfe27cbec54e4254de2073d0d

**Description:** Prepare older Build Versions of Whonix for Upgrade
 Applies fixes required for upgrading from for example Whonix 8.x to Whonix
 9.x etc.
 .
 Upgrades from Whonix 7.x or older versions is unsupported.
 .
 Safe to remove.



## libvirt-dist

**Package:** libvirt-dist

**Version:** 3:8.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  104

**Recommends:**  

**Conficts:**  whonix-libvirt

**Replaces:**  whonix-libvirt

**Provides:**  whonix-libvirt

**Homepage:**  [https://github.com/Whonix/libvirt-dist](https://github.com/Whonix/libvirt-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/libv/libvirt-dist/libvirt-dist_8.3-1_all.deb

**Size:**  104

**Sha256:**  518ce6697c3943393758fd892c649e8caf01fe1e4403db088b373a19f09142b2

**Sha1:**  56e25b29c509462b520a2e17dd2af4116df61377

**Md5sum:**  5ad9c625a3b7cf43965595234855c009

**Description:** Whonix Libvirt XML Files for KVM and QEMU
 Libvirt XML files for Whonix-Gateway, Whonix-Workstation,
 Whonix-Custom-Workstation and Whonix's internal network.
 .
 Whonix-Host grub branding, motd and issue banner.
 .
 Whonix-Host boot popup.
 .
 See also:
 - https://www.whonix.org/wiki/KVM
 - https://www.whonix.org/wiki/QEMU



## live-config-dist

**Package:** live-config-dist

**Version:** 3:2.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  155

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/live-config-dist](https://github.com/Whonix/live-config-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/l/live-config-dist/live-config-dist_2.0-1_all.deb

**Size:**  155

**Sha256:**  d32f9b56a917f83f035c5fde460839cc84e385719fac55a02c8def752c299c6b

**Sha1:**  3836d47f35a6b84fa8c63bcfbb4bdd8b894be60b

**Md5sum:**  8bf50c9ffeb1aaba78bd66983efde657

**Description:** calamares-settings-whonix and maybe calamares-settings-kicksecure
 Installed in Host ISO Live.
 .
 Supposed to be removed in Host installed.
 .
 Enables autologin for Host ISO Live.



## lkrg

**Package:** lkrg

**Version:** 0.9.6.0-1

**Architecture:**  all

**Maintainer:**  Mikhail Morfikov <mmorfikov@gmail.com>

**Installed_size:**  16

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://lkrg.org](https://lkrg.org)

**Priority:**  optional

**Section:** kernel

**Filename:**  pool/main/l/lkrg/lkrg_0.9.6.0-1_all.deb

**Size:**  16

**Sha256:**  4e37d06a198d82176c46eadf75dc65b5420677c5a3166cbbd083e3291cbb6762

**Sha1:**  92b4e1d106061d395c99850f77f40cbdd9cf0b1b

**Md5sum:**  bde2d5bb69387ca1c75c4fa959e9249a

**Description:** Linux Kernel Runtime Guard (LKRG)
 LKRG performs runtime integrity checking of the Linux kernel and detection of
 security vulnerability exploits against the kernel.
 .
 LKRG is a kernel module (not a kernel patch), so it can be built for and loaded
 on top of a wide range of mainline and distros' kernels, without needing to
 patch those.
 .
 That is only a dependency package to install the LKRG kernel module and also
 some systemd service in order to help to manage loading/unloading the module at
 system boot/shutdown.



## lkrg-dkms

**Package:** lkrg-dkms

**Version:** 0.9.6.0-1

**Architecture:**  all

**Maintainer:**  Mikhail Morfikov <mmorfikov@gmail.com>

**Installed_size:**  787

**Recommends:**  lkrg-systemd (= 0.9.6.0-1)

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://lkrg.org](https://lkrg.org)

**Priority:**  optional

**Section:** kernel

**Filename:**  pool/main/l/lkrg/lkrg-dkms_0.9.6.0-1_all.deb

**Size:**  787

**Sha256:**  28485125a5ef6520e64cf3ff9007cf9e1995d4b822b06c3048981cc851504f5a

**Sha1:**  7758e89ec43fdbe1a7afc6a7d2235cbb4af26de9

**Md5sum:**  76d45e17aa3afc16131683b384cc927b

**Description:** Linux Kernel Runtime Guard (LKRG) Source Code and DKMS
 LKRG performs runtime integrity checking of the Linux kernel and detection of
 security vulnerability exploits against the kernel.
 .
 LKRG is a kernel module (not a kernel patch), so it can be built for and loaded
 on top of a wide range of mainline and distros' kernels, without needing to
 patch those.
 .
 This package uses DKMS to automatically build the LKRG kernel module.



## lkrg-systemd

**Package:** lkrg-systemd

**Version:** 0.9.6.0-1

**Architecture:**  all

**Maintainer:**  Mikhail Morfikov <mmorfikov@gmail.com>

**Installed_size:**  24

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://lkrg.org](https://lkrg.org)

**Priority:**  optional

**Section:** kernel

**Filename:**  pool/main/l/lkrg/lkrg-systemd_0.9.6.0-1_all.deb

**Size:**  24

**Sha256:**  8ade44fed9dc060ca65867de6dc80157d7db94dad8531d72edff1ede87e32aa7

**Sha1:**  3a56868680f8dcc9a261e0740529dc18d2b2bc67

**Md5sum:**  177cd0c8061766faa21ec3bb989ff663

**Description:** Systemd integration for Linux Kernel Runtime Guard (LKRG)
 LKRG performs runtime integrity checking of the Linux kernel and detection of
 security vulnerability exploits against the kernel.
 .
 LKRG is a kernel module (not a kernel patch), so it can be built for and loaded
 on top of a wide range of mainline and distros' kernels, without needing to
 patch those.
 .
 This package provides systemd integration for the LKRG kernel module.



## mediawiki-shell

**Package:** mediawiki-shell

**Version:** 3:1.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  94

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/mediawiki-shell](https://github.com/Kicksecure/mediawiki-shell)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/m/mediawiki-shell/mediawiki-shell_1.1-1_all.deb

**Size:**  94

**Sha256:**  396ba89138b5c1d9728d6bc618ad6965cf23c866b115a1ac662b64a8584d973d

**Sha1:**  094a30c066be1670428fd9c2fbe71cfc8e08f52c

**Md5sum:**  4473ed36914566622c71e0ea1f71f5f3

**Description:** bash shell scripts for usage of MediaWiki API
 Description here.
 .
 TODO



## msgcollector

**Package:** msgcollector

**Version:** 3:8.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  177

**Recommends:**  

**Conficts:**  diverts-etc++bash.bash+-+logout

**Replaces:**  

**Provides:**  diverts-etc++bash.bash+-+logout

**Homepage:**  [https://www.whonix.org](https://www.whonix.org)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/m/msgcollector/msgcollector_8.7-1_all.deb

**Size:**  177

**Sha256:**  fdc98b2cea425a85a06b731fbaa1d98f258f91ab32d48b279e00f8afa2472bd2

**Sha1:**  12a02f5d1db25e94dbd2c2530100a9269449f957

**Md5sum:**  8013d9b8e50f70dfe613a832ca86f913

**Description:** Command Line Interface Messages Toolkit Library
 A programming library providing an application programming interface (API)
 that allows the programmer to output colored text in terminal user interfaces
 (CLI).
 .
 Applications can send messages to msgcollector which it collects and
 dispatches once instructed to do so by the application.
 .
 For clarity and avoidance of confusion, msgcollector does not collect any
 data. Applications that do not use msgcollector do not interact with
 msgcollector. It is roughly in the same category as ncurses but has of course
 much less and very different features.
 .
 For graphical user interface (GUI) support also install package
 msgcollector-gui.



## msgcollector-gui

**Package:** msgcollector-gui

**Version:** 3:8.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  36

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org](https://www.whonix.org)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/m/msgcollector/msgcollector-gui_8.7-1_all.deb

**Size:**  36

**Sha256:**  5a55c23b1b2ace13e119fd7d75a7de5225450881a0d63112928064d09311f1b1

**Sha1:**  68ed179c20ccf9b5db70f51b33fea6b00a5be16c

**Md5sum:**  6bd1d075905784158ce6b8ae30c581d0

**Description:** Graphical User Interface Toolkit Library
 A programming library providing an application programming interface (API)
 that allows the programmer to output colored text in graphical user interfaces
 (GUI).
 .
 Applications can send messages to msgcollector which it collects and
 dispatches once instructed to do so by the application.
 .
 For clarity and avoidance of confusion, msgcollector does not collect any
 data. Applications that do not use msgcollector do not interact with
 msgcollector. It is roughly in the same category as Qt or GDK but has of
 course much less and very different features.
 .
 A metapackage that installs required dependencies for graphical user interface
 support.



## non-qubes-audio

**Package:** non-qubes-audio

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/non-qubes-audio_26.1-1_all.deb

**Size:**  66

**Sha256:**  305f5a63283ba37e3ae263c1b8bd826f326da3cd982ffc4d524bbe2c11785dc8

**Sha1:**  9cdcde859c0ec200893a3cb0c838615bbb98b4ff

**Md5sum:**  3d60a901046539a33895e6e8fb868a64

**Description:** Recommended packages for Audio Support in non-Qubes
 A metapackage, which includes recommended packages which are useful to provide
 audio support.
 .
 These are not useful in Qubes, since Qubes
 already has its own native audio implementation.
 .
 Safe to remove, if you know what you are doing.



## non-qubes-vm-enhancements-cli

**Package:** non-qubes-vm-enhancements-cli

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/non-qubes-vm-enhancements-cli_26.1-1_all.deb

**Size:**  66

**Sha256:**  caf51b960dcd2edc8d9c8762c4a94a39c197a1140128a7942357c3791f7a7484

**Sha1:**  ad511dcd7ae413e926a5c50e4f65765fa60bbb0c

**Md5sum:**  c57ea0b75743bd95f7af0eead4b3baef

**Description:** Recommended packages for terminal based VMs CLI
 A metapackage, which includes recommended packages which are useful within
 CLI based non-Qubes virtual machines.
 These are not useful in Qubes, since Qubes
 already has native implementations for those.
 .
 Safe to remove, if you know what you are doing.



## non-qubes-vm-enhancements-gui

**Package:** non-qubes-vm-enhancements-gui

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/non-qubes-vm-enhancements-gui_26.1-1_all.deb

**Size:**  66

**Sha256:**  ceab5de2d80bc8784a281b2733fd446f9a20bc684ab9573557465429a6ce375f

**Sha1:**  a6387c654359b4a05379a35f6524665c9f7638d0

**Md5sum:**  23b3cccbfbd00c2f075ae5f219f2d5dc

**Description:** Recommended packages for graphical VMs GUI
 A metapackage, which includes recommended packages which are useful within
 GUI based non-Qubes virtual machines.
 These are not useful in Qubes, since Qubes
 already has native implementations for those.
 .
 Safe to remove, if you know what you are doing.



## non-qubes-whonix-gateway-cli

**Package:** non-qubes-whonix-gateway-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/non-qubes-whonix-gateway-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  c34b4762b06e2cd326633b09306277c13be15e0672c27efd960d38efb1b8e377

**Sha1:**  a674d6763ab84aabea4100788f0153cd350a9967

**Md5sum:**  c3cac0c6d10b65294b7e76affdc77687

**Description:** Default Packages for Non-Qubes-Whonix-Gateway CLI
 A metapackage, which installs packages, for a
 Non-Qubes-Whonix-Default-Gateway without graphical user interface (GUI).
 .
 Do not remove.



## non-qubes-whonix-gateway-xfce

**Package:** non-qubes-whonix-gateway-xfce

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/non-qubes-whonix-gateway-xfce_23.0-1_all.deb

**Size:**  63

**Sha256:**  840ea6ef4daaf804bd8b30a6a66bd53642036a0088cb901fb73a8970d9c336be

**Sha1:**  1eb9a9356799b83e67ad8e1abac8f77fd1283804

**Md5sum:**  9f677abb74e5eccd6e4e5188d923b25c

**Description:** Default Packages for Non-Qubes-Whonix-Gateway Xfce GUI
 A metapackage, which installs packages, for a
 Non-Qubes-Whonix-Default-Gateway with Xfce.
 .
 Depends on kicksecure-desktop-environment-essential-xfce because that is
 required in Non-Qubes-Whonix Xfce in order to get graphical desktop
 environment.
 .
 Do not remove.



## non-qubes-whonix-workstation-cli

**Package:** non-qubes-whonix-workstation-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/non-qubes-whonix-workstation-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  23b7e5cf67c72667534367113e25e3aec94a2074bfaf0d3314166cecb8316f7b

**Sha1:**  7afeb84cffe2d375d44d323162753b64dd8a35d3

**Md5sum:**  82f966eab897db5e50d63a84dd76a6ea

**Description:** Default Packages for Non-Qubes-Whonix-Workstation CLI
 A metapackage, which installs packages, for a
 Non-Qubes-Whonix-Default-Workstation without graphical user interface (GUI).
 .
 Do not remove.



## non-qubes-whonix-workstation-xfce

**Package:** non-qubes-whonix-workstation-xfce

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/non-qubes-whonix-workstation-xfce_23.0-1_all.deb

**Size:**  63

**Sha256:**  359fb672e30118bfe2dffbccc911c1890543b9677ecec5c816058fff7867d704

**Sha1:**  ed3498a80136dbad2e2cc9a2f24b82f9b4ca213c

**Md5sum:**  0aa8ebd3ea4cfac2b28621a9bbdcab49

**Description:** Default Packages for Non-Qubes-Whonix-Workstation Xfce GUI
 A metapackage, which installs packages, for a
 Non-Qubes-Whonix-Default-Workstation with Xfce.
 .
 Depends on kicksecure-desktop-environment-essential-xfce because that is
 required in Non-Qubes-Whonix Xfce in order to get graphical desktop
 environment.
 .
 Do not remove.



## onion-grater

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



## open-link-confirmation

**Package:** open-link-confirmation

**Version:** 3:4.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  53

**Recommends:**  tb-starter, tb-updater, tb-default-browser

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/open-link-confirmation](https://github.com/Whonix/open-link-confirmation)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/o/open-link-confirmation/open-link-confirmation_4.9-1_all.deb

**Size:**  53

**Sha256:**  ff1c0150f9c537717e2cec5e4705c8834aa7a62e88c894c91e0be2d0057650e7

**Sha1:**  63e1413287b0724005243ae900bfa64ee2c1b59a

**Md5sum:**  469c53540b8735d16d4cd1eb53a57e43

**Description:** Asks for confirmation before opening links
 Asks before a link is (accidentally) opened in a browser. Links are opened in
 x-www-browser.
 .
 Currently only the Tor Browser starter from the tb-starter package (by Whonix
 developers) supports using open-link-confirmation. Shell wrappers could be
 written to support other browsers as well.
 .
 On an Anonymity Gateway (when the anon-gw-base-files package is installed), it
 honors the $EDITOR environment variable (falls back to kwrite if unset), asks
 if a file should be opened in an editor before opening it and informs, that
 opening links on a Gateway is unsupported for security reasons.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## orca-screen-reader-support

**Package:** orca-screen-reader-support

**Version:** 3:26.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  66

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/kicksecure-meta-packages](https://github.com/Kicksecure/kicksecure-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/k/kicksecure-meta-packages/orca-screen-reader-support_26.1-1_all.deb

**Size:**  66

**Sha256:**  4194a991e57636095b2d6870782018266c6241fbc391cf38f2c068b5590aaa8e

**Sha1:**  27e0ad9393355c4b75611f98b8a9f77fd50e6061

**Md5sum:**  4ebd48bde711339333d520909505caba

**Description:** dependencies for the orca screen reader
 A metapackage, which includes depencency packages for the orca screen reader.
 .
 Safe to remove if its removal does not remove another metapackage, which is
 not safe to remove.



## qubes-whonix

**Package:** qubes-whonix

**Version:** 1:17.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  241

**Recommends:**  

**Conficts:**  diverts-etc++qubes-rpc++qubes.+s+et+d+ate+t+ime, diverts-etc++qubes-rpc++qubes.+s+ync+n+tp+c+lock, diverts-usr++lib++qubes++qubes-setup-dnat-to-ns, diverts-usr++share++qubes-updates-cache++errors+++e++r++r++-++i++n++v++a++l++i++d++-++u++r++l+, diverts-usr++share++tinyproxy++default.html

**Replaces:**  

**Provides:**  diverts-etc++qubes-rpc++qubes.+s+et+d+ate+t+ime, diverts-etc++qubes-rpc++qubes.+s+ync+n+tp+c+lock, diverts-usr++lib++qubes++qubes-setup-dnat-to-ns, diverts-usr++share++qubes-updates-cache++errors+++e++r++r++-++i++n++v++a++l++i++d++-++u++r++l+, diverts-usr++share++tinyproxy++default.html

**Homepage:**  [https://github.com/Whonix/qubes-whonix](https://github.com/Whonix/qubes-whonix)

**Priority:**  optional

**Section:** admin

**Filename:**  pool/main/q/qubes-whonix/qubes-whonix_17.3-1_all.deb

**Size:**  241

**Sha256:**  6538d6ce36973d5ff14c3349886fcbd39b9d3808c02f54b0b8a65e2bab035b4b

**Sha1:**  ac9503c304a00287298152b7338b9aad75550578

**Md5sum:**  1c067f3e1ca03fc7bade20c32a4acccd

**Description:** Qubes Configuration for Whonix-Gateway and Whonix-Workstation
 This package contains all the scripts and configuration options to be able
 to run Whonix-Gateway and Whonix-Workstation within a Qubes environment.
 .
 Whonix-Gateway should run as a ProxyVM.
 .
 Whonix-Workstation should run as an AppVM.
 .
 Template updates over Tor.



## qubes-whonix-gateway

**Package:** qubes-whonix-gateway

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/qubes-whonix-gateway_23.0-1_all.deb

**Size:**  63

**Sha256:**  00e7f585f94136ca7d2deef03a8979544c8c19a724f5b789f596ecbb50b8532e

**Sha1:**  77783895a45b8fb010691bb12f66010d733e1ba9

**Md5sum:**  50882cc60b924c1bbbfe2421efa2da81

**Description:** Default packages for Qubes-Whonix-Gateway
 A metapackage, which installs packages, for a
 Qubes-Whonix-Default-Gateway.
 .
 Only depends on whonix-gateway-shared-packages-shared-meta,
 because installing kicksecure-desktop-environment-essential-gui is not required
 in Qubes-Whonix.
 .
 Do not remove.



## qubes-whonix-gateway-packages-recommended

**Package:** qubes-whonix-gateway-packages-recommended

**Version:** 1:17.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  61

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/qubes-whonix](https://github.com/Whonix/qubes-whonix)

**Priority:**  optional

**Section:** admin

**Filename:**  pool/main/q/qubes-whonix/qubes-whonix-gateway-packages-recommended_17.3-1_all.deb

**Size:**  61

**Sha256:**  7ab50e175171567c5ea40ccee5b7dcf7ef23ea2e475bb36d464721b02f6bd650

**Sha1:**  7bbd08a6dee95985e673603c399fbd2766851302

**Md5sum:**  bd9a457f9d0a79a89fc496e4b8a0cd64

**Description:** Recommended packages for Qubes-Whonix-Gateway
 A metapackage, which installs packages, which are recommended for
 Qubes-Whonix-Gateway.
 .
 Safe to remove, if you know what you are doing.



## qubes-whonix-shared-packages-recommended

**Package:** qubes-whonix-shared-packages-recommended

**Version:** 1:17.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  61

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/qubes-whonix](https://github.com/Whonix/qubes-whonix)

**Priority:**  optional

**Section:** admin

**Filename:**  pool/main/q/qubes-whonix/qubes-whonix-shared-packages-recommended_17.3-1_all.deb

**Size:**  61

**Sha256:**  ef9bc89fea59aeb8c29530ddbc143c9d5a5856f3e216dc9d8bf3380b8af8ebb5

**Sha1:**  f9dac69b6be9a2ea1504b74ac9cd8d7a4fc69e29

**Md5sum:**  6d8319805753c0c570958a57f5f21c47

**Description:** Recommended packages for Qubes-Whonix-Gateway and Qubes-Whonix-Workstation
 A metapackage, which includes recommended packages to ensure, Qubes-Whonix
 standard tools are available and other useful recommended packages.
 .
 Safe to remove, if you know what you are doing.



## qubes-whonix-workstation

**Package:** qubes-whonix-workstation

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/qubes-whonix-workstation_23.0-1_all.deb

**Size:**  63

**Sha256:**  147b602cdbdd109eeab103a05b5498273748a0070c6407e14b61759ad082ce18

**Sha1:**  f91f475f223d1990a58856d3cb338d5d8a2ab3da

**Md5sum:**  5ce159b5566df4c3bb04e48a023c3b32

**Description:** Default packages for Qubes-Whonix-Workstation
 A metapackage, which installs packages, for a
 Qubes-Whonix-Default-Workstation.
 .
 Only depends on whonix-workstation-shared-packages-shared-meta,
 because installing kicksecure-desktop-environment-essential-gui is not required
 in Qubes-Whonix.
 .
 Do not remove.



## qubes-whonix-workstation-packages-recommended

**Package:** qubes-whonix-workstation-packages-recommended

**Version:** 1:17.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  61

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/qubes-whonix](https://github.com/Whonix/qubes-whonix)

**Priority:**  optional

**Section:** admin

**Filename:**  pool/main/q/qubes-whonix/qubes-whonix-workstation-packages-recommended_17.3-1_all.deb

**Size:**  61

**Sha256:**  c6f3393de97d08b34245f84aee401e4c89c06d461f06028aeb562043da09a783

**Sha1:**  a0a6aac176562e7d9a67887bd3cb9242ae8e90a4

**Md5sum:**  cf1539f9c97cd503ac609d37144c5adb

**Description:** Recommended packages for Qubes-Whonix-Workstation
 A metapackage, which installs packages, which are recommended for
 Qubes-Whonix-Workstation.
 .
 Feel free to remove, if you know what you are doing.



## rads

**Package:** rads

**Version:** 3:6.1-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  80

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/rads](https://github.com/Whonix/rads)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/r/rads/rads_6.1-1_all.deb

**Size:**  80

**Sha256:**  3123f026f48ea2550d7030d614ed787fd9655912d6fdb640b6f367066aa83956

**Sha1:**  c497feb5ab198bc6166ef3bccec61ecc64e37763

**Md5sum:**  9117201055b9587c069966926ad98853

**Description:** RAM Adjusted Desktop Starter
 If there is more than X MB RAM in total, the desktop environment will be
 started.
 .
 If less than X MB RAM in total (for example, only 196 MB RAM in total), no
 desktop environment will be started.
 .
 This should be quite convenient, because users with low RAM could reduce Y MB
 and even if they sometimes wanted to configure/check something, they could
 assign 512 RAM and automagically boot into the graphical desktop. There are
 also many settings in /etc/rads.d/ (stackable) to configure this feature, so
 if you want, you can also add a lot RAM, but not boot into a desktop
 environment, or use different display managers and so on.
 .
 Most useful in virtual machines.



## ram-wipe

**Package:** ram-wipe

**Version:** 3:1.4-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  72

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Kicksecure/ram-wipe](https://github.com/Kicksecure/ram-wipe)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/r/ram-wipe/ram-wipe_1.4-1_all.deb

**Size:**  72

**Sha256:**  4220b6c71699aa390460368a1e1cd42a343c720fe7b45064752998e4fae1f412

**Sha1:**  f1aa9ad25ff90e195eb8a4476799ca1c910fd86d

**Md5sum:**  0aa159666c85f1ceab9d202899573f6e

**Description:** Wipe RAM on shutdown and reboot
 A dracut module that wipes RAM on shutdown and reboot.
 .
 Not implemented for initramfs.



## repository-dist

**Package:** repository-dist

**Version:** 3:9.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  160

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Project-APT-Repository](https://www.whonix.org/wiki/Project-APT-Repository)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/r/repository-dist/repository-dist_9.0-1_all.deb

**Size:**  160

**Sha256:**  a299c8ed22a41b1ff3600cf901cfa3892624a94f65bed13380ea50b45ea3e260

**Sha1:**  417d62e9a4492fca675716abfaa6a6d0e059b186

**Md5sum:**  12901acc4fbe2be9996b928b399bed75

**Description:** Derivative APT Repository Command Line Interface (CLI)
 This tool can always be used to enable either Derivative's stable, testers or
 developers repository or to disable Derivative's repository.
 .
 Derivative's APT Repository is not enabled by default. Some users prefer this
 for trust/security reasons.
 .
 On first boot of Derivative, the Derivative Repository Tool gets automatically
 started by setup-dist. The user is free to either leave Derivative's
 repository disabled or to configure it as desired.
 .
 Technically speaking, this tool creates or deletes file
 `/etc/sources.list.d/derivative.list`.
 .
 Using APT `signed-by`.



## repository-dist-wizard

**Package:** repository-dist-wizard

**Version:** 3:9.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  32

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Project-APT-Repository](https://www.whonix.org/wiki/Project-APT-Repository)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/r/repository-dist/repository-dist-wizard_9.0-1_all.deb

**Size:**  32

**Sha256:**  09e00ee05e0a1eb8560c2f92e63ebd7fae4317b25530c1535dec0f66c8c7e6bc

**Sha1:**  e153dad146264698e6c1ea9e38bf0ce48dcdda14

**Md5sum:**  e6fb6630db5efe9a11891576eb056b77

**Description:** Derivative APT Repository Graphical User Interface (GUI)
 This tool can always be used to enable either Derivative's stable, testers or
 developers repository or to disable Derivative's repository.
 .
 This is a metapackage depending on the required packages for the GUI
 (Graphical User Interface).



## ro-mode-init

**Package:** ro-mode-init

**Version:** 3:2.1-1

**Architecture:**  all

**Maintainer:**  Algernon <33966997+Algernon-01@users.noreply.github.com>

**Installed_size:**  28

**Recommends:**  

**Conficts:**  grub-default-live, grub-live

**Replaces:**  grub-default-live, grub-live

**Provides:**  boot-live

**Homepage:**  [https://github.com/Whonix/ro-mode-init](https://github.com/Whonix/ro-mode-init)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/r/ro-mode-init/ro-mode-init_2.1-1_all.deb

**Size:**  28

**Sha256:**  6a0043145a4a15fff18ae8ce4bf26c77cec2cc27125ecdd7cb32808158a58903

**Sha1:**  600b9d4e286f17d04a77cb416af4e59feaac8d36

**Md5sum:**  5fe84833485b9223fcc9d8dbe343f070

**Description:** Detects read-only disks and automatically enables live-boot
 Allows booting the system in live mode. Meaning, no persistent modifications
 will be written to the disk. All changes stay in RAM.
 .
 No claims are made with regard to anti forensics.



## sandbox-app-launcher

**Package:** sandbox-app-launcher

**Version:** 0:5.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  98

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/sandbox-app-launcher](https://github.com/Whonix/sandbox-app-launcher)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/sandbox-app-launcher/sandbox-app-launcher_5.7-1_all.deb

**Size:**  98

**Sha256:**  a3794c819dd3a56d5d3f004ec503ed3028a5f23e253262d90fee50f901ec7b04

**Sha1:**  5bc4cd7f1d0de03a0ce61cd1acac9b9ae404a446

**Md5sum:**  bcc5dc8d9842f8951f946aef858a5562

**Description:** application launcher to start apps in a restrictive sandbox
 sandbox-app-launcher runs each app as its own user, in a bubblewrap sandbox
 and confined by apparmor.
 .
 The directory, `/shared`, is shared across all app sandboxes to transfer
 files across.
 .
 This implements a permissions system to configure what apps can access.
 There are currently 5 available permissions:
 .
  * Network access
 .
  * Webcam access
 .
  * Microphone access
 .
  * Shared storage access (read-only or read-write)
 .
  * Dynamic native code execution
 .
 All apps the user installs will be automatically configured to run in
 the sandbox and a prompt will ask the user which permissions they wish to
 grant the application (not implemented yet).
 .
 Currently a WIP and not for actual use.



## sdwdate

**Package:** sdwdate

**Version:** 3:21.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  304

**Recommends:**  timesanitycheck, bootclockrandomization

**Conficts:**  time-daemon

**Replaces:**  

**Provides:**  time-daemon

**Homepage:**  [https://github.com/Whonix/sdwdate](https://github.com/Whonix/sdwdate)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/sdwdate/sdwdate_21.7-1_all.deb

**Size:**  304

**Sha256:**  dab13e95180fa57002c5dc76a9e608fe37976a3401e503e4af04b1139250bc9f

**Sha1:**  771e0cff045068f0fb4846c857d870195fd6e29a

**Md5sum:**  d2f1e37605947ca75f5ab6a910465b22

**Description:** Secure Distributed Network Time Synchronization
 Time keeping is crucial for security, privacy, and anonymity. Sdwdate is a Tor
 friendly replacement for rdate and ntpdate that sets the system's clock by
 communicating via onion encrypted TCP with Tor onion webservers.
 .
 At randomized intervals, sdwdate connects to a variety of webservers and
 extracts the time stamps from http headers (RFC 2616).
 Using sclockadj option, time is gradually adjusted preventing bigger clock
 jumps that could confuse logs, servers, Tor, i2p, etc.
 .
 This package contains the sdwdate time fetcher and daemon. No
 installation on remote servers required. To avoid conflicts, this daemon
 should not be enabled together with ntp or tlsdated.



## sdwdate-gui

**Package:** sdwdate-gui

**Version:** 1:8.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  206

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Dev/TimeSync](https://www.whonix.org/wiki/Dev/TimeSync)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/sdwdate-gui/sdwdate-gui_8.2-1_all.deb

**Size:**  206

**Sha256:**  7d89613aa6cb2bfe3b3e04dca7eb97eee09e2335ecfb5e8e9d2baee9bf3b198c

**Sha1:**  94001f794ecd560c85deac40a00a14a12e31334f

**Md5sum:**  f53472c0429c1c2a0d639e573dd5f9a6

**Description:** Sdwdate Monitor
 sdwdate-gui is a systray icon monitor for sdwdate: checks sdwdate's status
 and modify the tray icon accordingly. In addition, it allows the user to
 restart sdwdate and view the log.



## security-misc

**Package:** security-misc

**Version:** 3:28.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  394

**Recommends:**  

**Conficts:**  

**Replaces:**  anon-gpg-tweaks, swappiness-lowest, tcp-timestamps-disable

**Provides:**  

**Homepage:**  [https://github.com/Whonix/security-misc](https://github.com/Whonix/security-misc)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/security-misc/security-misc_28.8-1_all.deb

**Size:**  394

**Sha256:**  cbbb6cf59a99c59f5c3dacbbafa3158c98618565edbbb66badc33b33bc8015c4

**Sha1:**  48bbe1c679aca30bb3c351ba320300929a28c2e0

**Md5sum:**  6f7e4858d6767e20473754a616b533e5

**Description:** Enhances Miscellaneous Security Settings
 https://github.com/Whonix/security-misc/blob/master/README.md
 .
 https://www.whonix.org/wiki/Security-misc
 .
 Discussion:
 .
 Happening primarily in Whonix forums.
 https://forums.whonix.org/t/kernel-hardening/7296



## serial-console-enable

**Package:** serial-console-enable

**Version:** 3:3.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  30

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/serial-console-enable](https://github.com/Whonix/serial-console-enable)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/serial-console-enable/serial-console-enable_3.2-1_all.deb

**Size:**  30

**Sha256:**  279e15d5076f58001fe8e3b4e92223131553158b775336884c763d3a502e0e96

**Sha1:**  a9569e592ad8d5e4e81f428da1d673fcfcbb699e

**Md5sum:**  b0ec4e06361c656bf5d905cea8d3a172

**Description:** Enables serial console
 Ships a /etc/default/grub.d/30_serial_console.cfg configuration file, that
 enables serial console.
 .
 Enables /lib/systemd/system/getty.target.wants/serial-getty@ttyS0.service by
 creating a symlink from:
 /lib/systemd/system/serial-getty@.service
 to:
 /lib/systemd/system/getty.target.wants/serial-getty@ttyS0.service
 .
 Useful for serial console login such as into Whonix KVM VMs from the host
 operating system.
 .
 Forum discussion:
 https://forums.whonix.org/t/how-do-i-enter-the-whonix-shell-from-cli/7271
 .
 Safe to remove if you do not require serial console login such as:
 virsh console vm-name



## setup-dist

**Package:** setup-dist

**Version:** 3:7.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  95

**Recommends:**  

**Conficts:**  whonixsetup

**Replaces:**  whonixsetup

**Provides:**  whonixsetup

**Homepage:**  [https://github.com/Kicksecure/setup-dist](https://github.com/Kicksecure/setup-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/setup-dist/setup-dist_7.2-1_all.deb

**Size:**  95

**Sha256:**  5cbddccf975309b2ffc57c4bd5cebd75feed352bc21f5f004183e48ecced11f1

**Sha1:**  b8b93f0acedd7acb79cdd052bd931d8ada4be76f

**Md5sum:**  d10f4ea401dc1e2c055e65a38293949f

**Description:** First Time Connection Setup
 When the derivative starts for the first time, it won't automatically connect
 to the public Tor network. This is useful for users who want to hide Tor from
 their ISP. setup-dist is automatically started, which educates about different
 methods to connect (public Tor network, bridges, etc.).
 .
 Also automatically starts the Derivative Repository Tool (if installed), so
 the user can decide whether to use Derivative Repository and if yes, choose
 which one.



## setup-wizard-dist

**Package:** setup-wizard-dist

**Version:** 3:7.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  96

**Recommends:**  icon-pack-dist

**Conficts:**  whonix-setup-wizard

**Replaces:**  whonix-setup-wizard

**Provides:**  whonix-setup-wizard

**Homepage:**  [https://www.whonix.org/](https://www.whonix.org/)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/setup-wizard-dist/setup-wizard-dist_7.8-1_all.deb

**Size:**  96

**Sha256:**  14e5ecfb9b922653da6013053c63b07b4dffb3cf89b63bde1d243cf35d2dcfa7

**Sha1:**  3f312ad42bdc565d8249fb35f5b344c467d4095a

**Md5sum:**  4b98c705f081e1a52bfe8d1774e9401e

**Description:** First Boot Setup
 When distribution starts for the first time, it won't automatically connect
 to the public Tor network. This is useful for users who want to hide Tor from
 their ISP. Anon Connection Wizard is automatically started, which educates
 about different methods to connect (public Tor network, bridges, etc.).
 .
 Also automatically starts the Distribution Repository Tool (if installed), so
 the user can decide whether to use Distribution's Repository and if yes,
 choose which one.



## swap-file-creator

**Package:** swap-file-creator

**Version:** 3:5.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  53

**Recommends:**  haveged, jitterentropy-rngd

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/swap-file-creator](https://github.com/Whonix/swap-file-creator)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/swap-file-creator/swap-file-creator_5.2-1_all.deb

**Size:**  53

**Sha256:**  7c95e0b5f6f4e7c35c0d5779e5aa063bab686a0bbc1ab6fb7a9cb0871fd1af2f

**Sha1:**  133e8ef8424c90eefaf3fa6d82ebc410ca21b81d

**Md5sum:**  3106156d378d71d375fb36eb1eb4b8ff

**Description:** Adds encrypted swap file to the system
 On every boot, creates a new encrypted swapfile with a random password.
 .
 Useful for systems with low RAM such as inside virtual machines.
 .
 Has a setting ENOUGH_RAM which defaults to 1950 MB. If there is more than
 enough RAM, no swap file will be created.
 .
 Has an option to shred the swapfile on shutdown.



## systemcheck

**Package:** systemcheck

**Version:** 3:25.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  394

**Recommends:**  icon-pack-dist

**Conficts:**  apparmor-profile-whonixcheck, whonixcheck

**Replaces:**  apparmor-profile-whonixcheck, whonixcheck

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/systemcheck](https://www.whonix.org/wiki/systemcheck)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/s/systemcheck/systemcheck_25.8-1_all.deb

**Size:**  394

**Sha256:**  f3531c27b63a0a24bfb48dc6edfc8e6a4f96c67a23760b3cc4de6bb2dc44da71

**Sha1:**  3817c054c7ee9f29895e4d4f92d949d3ae391c80

**Md5sum:**  3d8bdd625d76619ec40a8e64aac9c1ff

**Description:** Anonymity and security check
 Checks many important aspects for better security.
 .
 Only checks things. Does not change things.
 .
 Safe to remove.



## tb-default-browser

**Package:** tb-default-browser

**Version:** 3:3.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  43

**Recommends:**  tb-updater, open-link-confirmation

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/tb-default-browser](https://github.com/Whonix/tb-default-browser)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tb-default-browser/tb-default-browser_3.9-1_all.deb

**Size:**  43

**Sha256:**  c97bc00e442631694df16d0d8259e936497b02b61dbd0b4fc88146e22507b912

**Sha1:**  5e61247c0258540747ec7c0cfd0cb7f1ccdc3909

**Md5sum:**  258d52545f68d560167a64fc689fb239

**Description:** Configures system to use /usr/bin/torbrowser as default browser
 Sets /usr/bin/x-www-browser to /usr/bin/torbrowser.
 .
 Sets /usr/bin/gnome-www-browser to /usr/bin/torbrowser.
 .
 Sets BROWSER environment variable to /usr/bin/x-www-browser by using
 /etc/profile.d/ and /etc/X11/Xsession.d/ hooks.
 .
 Registers of MIME type handlers to 'torbrowser'.
 .
 Sets KDE's default browser to x-www-browser. This only takes effect for newly
 created user accounts. Not for existing user accounts. This is most useful to
 help Linux distribution maintainers setting divergent defaults.
 .
 See also:
 The Default Browser on Linux Debacle
 http://blog.codef00.com/2011/02/18/the-default-browser-on-linux-debacle/
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## tb-starter

**Package:** tb-starter

**Version:** 3:14.8-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  132

**Recommends:**  tb-updater, tb-default-browser, open-link-confirmation, icon-pack-dist

**Conficts:**  

**Replaces:**  

**Provides:**  torbrowser-launcher

**Homepage:**  [https://github.com/Whonix/tb-starter](https://github.com/Whonix/tb-starter)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tb-starter/tb-starter_14.8-1_all.deb

**Size:**  132

**Sha256:**  93367f1e4e8bffb3fad1d0f54d5641fa64695712a54dc57b780b77c025f534c2

**Sha1:**  ea43111b63dc1ea30640d4ec12476bcb909ba908

**Md5sum:**  9b57391c01489ee9759ec2ee59926560

**Description:** Tor Browser Starter (by Whonix developers)
 Both, a starter for Tor Browser.
 Provides security hardening, integration with Debian, Whonix and Qubes.
 .
 Starter.
 .
  - Tor Browser Starter start menu entry and `/usr/bin/torbrowser`
 starter. Starts `/home/user/.tb/tor-browser/start-tor-browser`.
 .
 When config option tb_hardening=true is set or when using
 command line option --hardening, firejail will be used.
 .
 Uses open-link-confirmation if available.
 .
 Prompts to install the browser if not yet installed.
 .
 Changes directory into browser directly before startup.
 .
 Custom homepage support.
 .
 Qubes integration.
 .
 Sanity tests:
  - Aborts if detected being run as root.
  - Aborts in Qubes TemplateVM.
  - Aborts in Qubes DVM Template.
  - Waits for Qubes mount dirs and gui agent being ready.
 .
 In Qubes AppVM copies browser from root image to private image at first start.
 .
 Tor Browser documentation by Whonix.
 .
  - https://www.whonix.org/wiki/Tor_Browser
  - https://www.whonix.org/wiki/Tor_Browser/Advanced_Users
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## tb-updater

**Package:** tb-updater

**Version:** 3:25.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  298

**Recommends:**  tb-starter, icon-pack-dist, helper-scripts

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/tb-updater](https://github.com/Whonix/tb-updater)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tb-updater/tb-updater_25.5-1_all.deb

**Size:**  298

**Sha256:**  d2f25863b0038d1087966f472b0de5b6ad64d711be0594fa1cea2e2a04459fbe

**Sha1:**  0b03b3cc246e45d30a86c7bb0dcf13397ccea6e3

**Md5sum:**  efbd3743cdffaafb61657b5686a273dd

**Description:** Tor Browser Downloader by Whonix developers
 Automates download and verification of Tor Browser from The Tor Project's
 website. Useful for initial installation of Tor Browser, clean
 re-installations of Tor Browser and keeping newly created Qubes AppVMs
 inherited from updated Qubes TemplateVMs can ship up to date versions of
 Tor Browsers.
 .
 Incapable of preserving of updating and preserving user data. Use
 Tor Browser's internal updater for that purpose. Notifies about already
 exiting installations of Tor Browser. Renamed rather than deletes old versions
 of Tor Browsers to avoid user data loss.
 .
 Has a cli and a gui mode. Can auto detect latest version numbers or use user
 configured version numbers. Comes with a download confirmation screen that
 lets users choose which version to download. [1] Has a installation
 confirmation screen [2] that enables users to detect indefinite freeze and
 rollback attacks.
 .
 Integrates well with tb-starter, tb-default-browser and
 open-link-confirmation package as well as with Qubes.
 .
 Without the helper-scripts package installed, the GUI will not move the
 progress bar.
 .
 If you have the helper-scripts package installed, it will show a nicer
 progress bar when run in terminal and more meaningful curl exit code
 messages, when curl failed.
 .
 When having the helper-scripts package installed (recommended for
 Anonymity Distributions), Tor Browser Downloader will check, that Tor is
 enabled, that no package manager is currently running and that Tor finished
 bootstrapping before download attempts.
 .
 Supports being run inside chroot and from Debian maintainer postinst script.
 .
 Qubes integration:
 .
  - Up-to-date browser versions made available to freshly created AppVMs and
 DispVMs.
  - In DispVM mounts browser folder which resides in root image to user home
 folder rather than copying for faster browser startup.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.
 .
 [1] https://www.whonix.org/wiki/Tor_Browser#Download_Confirmation_Screen
 [2] https://www.whonix.org/wiki/Tor_Browser#Installation_Confirmation_Screen



## timesanitycheck

**Package:** timesanitycheck

**Version:** 3:5.2-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  45

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/wiki/Dev/TimeSync](https://www.whonix.org/wiki/Dev/TimeSync)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/timesanitycheck/timesanitycheck_5.2-1_all.deb

**Size:**  45

**Sha256:**  867d8ec1dd6e53ec371a8514f7c406a4d8778b86d1bd13e5459643df540ba0a1

**Sha1:**  4b4f5f66286932e08dae7e8536660c4636c82b26

**Md5sum:**  1c2cdf8ec09a76256da357fd37b0e961

**Description:** Checks if the system clock is sane between build timestamp and expiration date
 Reports, if clock is sane and not slower than build timestamp or faster than
 expiration date (configurable, default currently set to 17 MAY 2033 10:00:00).
 .
 This should catch situations, where the host's clock is too much off (CMOS
 battery defect, user mistakenly set a very wrong date, etc.), resulting in
 network time synchronization tools (such as sdwdate) no longer being able to
 correct the clock; catch eventual bigger bugs in network time synchronization
 tools; and some types of attacks on network time synchronization.



## tor-control-panel

**Package:** tor-control-panel

**Version:** 1:4.3-1

**Architecture:**  all

**Maintainer:**  troubadour <trobador@riseup.net>

**Installed_size:**  152

**Recommends:**  tor, obfs4proxy

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://www.whonix.org/](https://www.whonix.org/)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tor-control-panel/tor-control-panel_4.3-1_all.deb

**Size:**  152

**Sha256:**  369ddf30a007ef6aaf024dd538d22b76f69a02883c05e1761be3551788c145be

**Sha1:**  35a234b03c7c4025ebbbabcfa0e1797b6e9c1dbd

**Md5sum:**  9ceb051d85baf90fa5b85791f3dd059d

**Description:** Tor Control Graphical User Interface
 WARNING: Not (yet) a standalone ready to use outside of Whonix:
 .
 tor-control-panel is a Tor controller.
 .
 tor-control-panel is produced independently from the Tor anonymity
 software and carries no guarantee from The Tor Project about quality,
 suitability or anything else.



## tor-ctrl

**Package:** tor-ctrl

**Version:** 3:4.9-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  77

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://gitweb.torproject.org/torspec.git/tree/control-spec.txt](https://gitweb.torproject.org/torspec.git/tree/control-spec.txt)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/t/tor-ctrl/tor-ctrl_4.9-1_all.deb

**Size:**  77

**Sha256:**  6b0cea040cdce508e5e90b373139bea16eb1d0cb8df32615de70d37bbc4147c5

**Sha1:**  c9b3e327274821dcdb58d20c7a5b1e12b72cd281

**Md5sum:**  239da648f6f2e9fcfdccc33d4b50f23c

**Description:** Tor controller command line tool
 Command line tool for setting up stream for communication from the
 Tor Controller's (client) to a Tor process (server). The client send
 commands using TCP sockets or Unix-domain sockets and receive replies
 from the server.
 .
 https://gitweb.torproject.org/torspec.git/tree/control-spec.txt
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## tor-geoipdb

**Package:** tor-geoipdb

**Version:** 0.4.7.13-1~d11.bullseye+1

**Architecture:**  all

**Maintainer:**  Peter Palfrader <weasel@debian.org>

**Installed_size:**  10798

**Recommends:**  

**Conficts:**  

**Replaces:**  tor (<< 0.2.4.8)

**Provides:**  

**Homepage:**  [https://www.torproject.org/](https://www.torproject.org/)

**Priority:**  optional

**Section:** net

**Filename:**  pool/main/t/tor/tor-geoipdb_0.4.7.13-1~d11.bullseye+1_all.deb

**Size:**  10798

**Sha256:**  ab5fefffb1cbf5b355276c685ebcbdd1ff62bf395780e6fa7fe9b0682ebc5e41

**Sha1:**  ab754d6ccfe9b9fd9a7202a0290dc4440b56ca35

**Md5sum:**  76ff4deff02eb27a953c19c93fbef8e1

**Description:** GeoIP database for Tor
 This package provides a GeoIP database for Tor, i.e. it maps IPv4 addresses
 to countries.
 .
 Bridge relays (special Tor relays that aren't listed in the main Tor
 directory) use this information to report which countries they see
 connections from.  These statistics enable the Tor network operators to
 learn when certain countries start blocking access to bridges.
 .
 Clients can also use this to learn what country each relay is in, so
 Tor controllers like arm or Vidalia can use it, or if they want to
 configure path selection preferences.



## usability-misc

**Package:** usability-misc

**Version:** 3:13.5-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  349

**Recommends:**  

**Conficts:**  

**Replaces:**  gpl-sources-download, grub-screen-resolution, scurl

**Provides:**  

**Homepage:**  [https://github.com/Whonix/usability-misc](https://github.com/Whonix/usability-misc)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/u/usability-misc/usability-misc_13.5-1_all.deb

**Size:**  349

**Sha256:**  88fe361371b7c95766581bea91a03da107d6a5a85de8e46ae2cb75fac22f15a3

**Sha1:**  6d74cd46b52dcaaa9b40f0211f84d5a952806908

**Md5sum:**  4cc6cdc50b57b88a6afe7d697bcbfe85

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



## uwt

**Package:** uwt

**Version:** 3:7.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  113

**Recommends:**  

**Conficts:**  diverts-etc++tor++torsocks.conf, diverts-usr++bin++apt, diverts-usr++bin++apt-file, diverts-usr++bin++apt-get, diverts-usr++bin++aptitude-curses, diverts-usr++bin++curl, diverts-usr++bin++dnf-3, diverts-usr++bin++git, diverts-usr++bin++gpg, diverts-usr++bin++gpg2, diverts-usr++bin++mixmaster-update, diverts-usr++bin++onionshare, diverts-usr++bin++onionshare-gui, diverts-usr++bin++rawdog, diverts-usr++bin++ricochet, diverts-usr++bin++ssh, diverts-usr++bin++wget, diverts-usr++bin++wormhole, diverts-usr++bin++yum, diverts-usr++bin++yumdownloader

**Replaces:**  

**Provides:**  diverts-etc++tor++torsocks.conf, diverts-usr++bin++apt, diverts-usr++bin++apt-file, diverts-usr++bin++apt-get, diverts-usr++bin++aptitude-curses, diverts-usr++bin++curl, diverts-usr++bin++dnf-3, diverts-usr++bin++git, diverts-usr++bin++gpg, diverts-usr++bin++gpg2, diverts-usr++bin++mixmaster-update, diverts-usr++bin++onionshare, diverts-usr++bin++onionshare-gui, diverts-usr++bin++rawdog, diverts-usr++bin++ricochet, diverts-usr++bin++ssh, diverts-usr++bin++wget, diverts-usr++bin++wormhole, diverts-usr++bin++yum, diverts-usr++bin++yumdownloader

**Homepage:**  [https://github.com/Whonix/uwt](https://github.com/Whonix/uwt)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/u/uwt/uwt_7.0-1_all.deb

**Size:**  113

**Sha256:**  b298751e2b3932a8381688586a157144ae1c6aac52538c38e49d08546134b096

**Sha1:**  72788141f3d2530c9bf17737ac3ce5a35fd90604

**Md5sum:**  2f236e57affaa0cbe012ecfd759db6c3

**Description:** Use Applications over Tor with Stream Isolation and Time Privacy
 Can add "torsocks" and/or "timeprivacy" before invocation of applications when
 configured to do so. For example, when simply typing "apt-get" instead of
 "torsocks apt-get", "apt-get" can still be routed over Tor.
 .
 The uwt package comes with the following applications pre-configured to use
 uwtwrapper, Tor and stream isolation:
  - apt
  - apt-file
  - apt-get
  - aptitude-curses
  - curl
  - git
  - gpg
  - gpg2
  - mixmaster-update
  - rawdog
  - ssh
  - wget
  - yum
  - yumdownloader
  - wormhole
 .
 To circumvent a uwt wrapper on a by case base, you append ".anondist-real" to
 the command, for example "apt-get.anondist-real". You can also deactivate
 specific or all uwt wrappers by using the stackable .d-style configuration
 folder /etc/uwt.d.
 .
 Uwt can only work only as good as torsocks. If torsocks is unable to route all
 of an application's traffic over Tor, ex. if there is an leak, there will
 also be one when using uwt. For that reason, it is recommended to use
 Anonymity Distributions, that prevent such leaks.
 .
 If an applications has native support for socks proxy settings, those should
 be preferred over uwt. Also refer to the TorifyHOWTO and your distribution's
 documentation.
 .
 Timeprivacy can keep your time private. You can create wrappers for
 applications and timeprivacy will feed those applications with a fake time,
 which obfuscates at which time you really used that applications (such as when
 you made the git commit or when you signed that document). It does NOT set
 your time zone to UTC.
 .
 This package is probably most useful for Anonymity Distributions.
 .
 This package is produced independently of, and carries no guarantee from,
 The Tor Project.



## vm-config-dist

**Package:** vm-config-dist

**Version:** 3:8.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  94

**Recommends:**  

**Conficts:**  

**Replaces:**  power-savings-disable-in-vms, shared-folder-help

**Provides:**  

**Homepage:**  [https://github.com/Whonix/vm-config-dist](https://github.com/Whonix/vm-config-dist)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/v/vm-config-dist/vm-config-dist_8.3-1_all.deb

**Size:**  94

**Sha256:**  2cd3450aebd4d3f58ad87701d909ec9f0d02b9176ed7789b74b82863eb93ab82

**Sha1:**  ebcc88960589680b948828fa8cf3e6cbfd1b725b

**Md5sum:**  700558c52426aeddbc2c43fe4201b211

**Description:** usability enhancements inside virtual machines
 Enables auto login for user `user` in `lightdm`.
 `/etc/lightdm/lightdm.conf.d/30_autologin.conf`
 https://www.whonix.org/wiki/Desktop#Disable_Autologin
 .
 Sets environment variable `QMLSCENE_DEVICE=softwarecontext` as workaround for
 "Automatic fallback to softwarecontext renderer".
 .
 It is not useful to open a screensaver or to power down the desktop for
 operating systems that are run inside VMs. There is no real display that could
 be saved and no real power that could be saved. From usability perspective it
 also is counter intuitive when looking at the VM window and only seeing a
 black screen. Therefore it makes sense to disable power savings in VMs.
 `/etc/X11/Xsession.d/20kde_screen_locker_disable_in_vms`
 `/etc/X11/Xsession.d/20software_rendering_in_vms`
 `/etc/X11/Xsession.d/20power_savings_disable_in_vms`
 `/etc/profile.d/20_power_savings_disable_in_vms.sh`
 `/usr/share/kde-power-savings-disable-in-vms/kdedrc`
 `/usr/share/kde-screen-locker-disable-in-vms/kscreenlockerrc`
 .
 Disables screen locker when running in VMs because that is not useful either.
 .
 Makes setting up a shared folder for virtual machines a bit easier.
 .
  * Creates a folder `/mnt/shared` with `chmod 777`, adds a group
 "vboxsf", adds user "user" to group "vboxsf". Facilitates auto-mounting of
 shared folders.
 .
  * Helps using shared folders with VirtualBox and KVM a bit
 easier (as in requiring fewer manual steps from the user).
 .
  * `/lib/systemd/system/mnt-shared-vbox.service`
  * `/lib/systemd/system/mnt-shared-kvm.service`
 .
 Set screen resolution 1920x1080 by default for VM in VirtualBox and KVM.
 Workaround for low screen resolution 1024x768 at first boot. When using lower
 screen resolutions, Xfce will automatically scale down.
 `/etc/skel/.config/xfce4/xfconf/xfce-perchannel-xml/displays.xml`
 .
 Installs VirtualBox guest additions if package
 `virtualbox-guest-additions-iso` is installed if environment variable
 `dist_build_virtualbox=true` or if running inside VirtualBox.
 (`systemd-detect-virt` returning `oracle`)
 `/usr/bin/vbox-guest-installer`



## whonix-base-files

**Package:** whonix-base-files

**Version:** 3:8.6-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  143

**Recommends:**  

**Conficts:**  diverts-etc++hostname, diverts-etc++hosts, diverts-etc++issue, diverts-etc++motd, diverts-etc++skel++.bashrc

**Replaces:**  anon-base-files, kicksecure-base-files, whonix-repository, whonix-setup-wizard, whonixcheck, whonixsetup

**Provides:**  diverts-etc++hostname, diverts-etc++hosts, diverts-etc++issue, diverts-etc++motd, diverts-etc++skel++.bashrc, kicksecure-base-files

**Homepage:**  [https://github.com/Whonix/whonix-base-files](https://github.com/Whonix/whonix-base-files)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/w/whonix-base-files/whonix-base-files_8.6-1_all.deb

**Size:**  143

**Sha256:**  3b442f7349b3c0fc4a55dd4825f8e97874c706aa1cd93fe850aa291a2f1f6125

**Sha1:**  0c3ebd783283d6e5adc2775a9833396a5db246fd

**Md5sum:**  ac469288c32387092339d725619c0f55

**Description:** Whonix base system miscellaneous files
 This package contains several important miscellaneous files, such as
 /etc/issue, /etc/motd, /etc/dpkg/origins/whonix,
 /etc/skel/.bashrc, /usr/bin/whonix, and others.
 .
 Anonymized operating system user name `user`, `/etc/hostname`, `/etc/hosts`,
 `/etc/machine-id`, `/var/lib/dbus/machine-id`, which should be shared among
 all anonymity distributions. See also:
 .
  * https://mailman.boum.org/pipermail/tails-dev/2013-January/002457.html
  * https://labs.riseup.net/code/issues/5655
  * http://lists.autistici.org/message/20140627.215105.24023267.en.html
 .
 Sets the WHONIX environment variable to 1 as well.
 .
 Ships marker files:
  * /usr/share/whonix/marker
  * /usr/share/anon-dist/marker



## whonix-firewall

**Package:** whonix-firewall

**Version:** 3:12.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  255

**Recommends:**  

**Conficts:**  ufw

**Replaces:**  whonix-gw-firewall, whonix-ws-firewall

**Provides:**  

**Homepage:**  [https://github.com/Whonix/whonix-firewall](https://github.com/Whonix/whonix-firewall)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/w/whonix-firewall/whonix-firewall_12.0-1_all.deb

**Size:**  255

**Sha256:**  7f4daaa4517b33fe210b51768c915988cdd8792418e7073ff0decd4b6dfa9017

**Sha1:**  cc2b84dc0da347852a5683ede6cfb23e8ff13bd3

**Md5sum:**  cced0b5149b282ee9ce1624ed2d0423e

**Description:** Firewall for Whonix-Gateway and Whonix-Workstation
 iptables rules script and firewall configuration file for Whonix-Gateway and
 Whonix-Workstation.
 .
 Whonix-Gateway Firewall Features:
  - transparent proxying
  - stream isolation
  - reject invalid packages
  - fail closed mechanism
  - optional VPN-Firewall
  - optional isolating proxy
  - optional incoming flash proxy
  - optional Tor relay
 .
 Do not remove, unless you no longer wish to use Whonix.



## whonix-gateway-default-applications-gui

**Package:** whonix-gateway-default-applications-gui

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-gateway-default-applications-gui_23.0-1_all.deb

**Size:**  63

**Sha256:**  432642f15e0cce46c477fe228f7e091ebc0d3bb7ad981ca93dbd2746540ed287

**Sha1:**  530fa39762f22e57e2f568022c6dab180d67ed81

**Md5sum:**  bceaa2f372593d2c0b7df3753238a9fa

**Description:** Recommended desktop packages for Whonix-Gateway GUI
 A metapackage, which installs graphical user interface (GUI) packages,
 which are recommended for a graphical Whonix-Gateway.
 .
 Safe to remove, if you know what you are doing.



## whonix-gateway-packages-dependencies-cli

**Package:** whonix-gateway-packages-dependencies-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-gateway-packages-dependencies-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  633983800c6296e151246b0e85b2b565b4d5ab03c4794a7dc7269a4e621dfe50

**Sha1:**  735da36931b3a7e491db80798a355ce827d763d5

**Md5sum:**  57de6b38140a360c2f0efcce33acf952

**Description:** Dependencies for Whonix-Gateway CLI
 A metapackage, which installs packages which Whonix-Gateway
 depends on.
 .
 Do not remove.



## whonix-gateway-packages-dependencies-pre

**Package:** whonix-gateway-packages-dependencies-pre

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-gateway-packages-dependencies-pre_23.0-1_all.deb

**Size:**  63

**Sha256:**  ca9c085c2dba12435ec28ff388bf001db136b6ea990a40b7f48333fc5efbbfca

**Sha1:**  a4e3e53b9a1423ffe0959e8dcf8e44adf0136196

**Md5sum:**  fad2c4954e541a777ac5d660ff5a550a

**Description:** Dependencies for Whonix-Gateway that changes network related files
 A metapackage, which installs packages which Whonix-Gateway
 depends on. Can not be merged into whonix-gateway-packages-dependencies due to
 conflicts with chroot build process.
 .
 Do not remove.



## whonix-gateway-rpi

**Package:** whonix-gateway-rpi

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-gateway-rpi_23.0-1_all.deb

**Size:**  63

**Sha256:**  1b10e159eee123b7c9212c683ef9f99c2f79aa3f9c92e6c350ca3be948192caf

**Sha1:**  8215c9106bc7de7cf08c1970bf2aa75f6b864237

**Md5sum:**  b892361f55b9b7f5abeacac09ed27b71

**Description:** Default packages for Whonix-Gateway-RPi CLI
 A metapackage, which installs packages for a CLI
 Raspberry Pi 3 Whonix-Gateway.
 .
 Do not remove.



## whonix-gateway-shared-packages-shared-meta

**Package:** whonix-gateway-shared-packages-shared-meta

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-gateway-shared-packages-shared-meta_23.0-1_all.deb

**Size:**  63

**Sha256:**  0804882e911236c682095e92f1ee57b088e59a99dfe36579907f65d73e24db7e

**Sha1:**  639193adc1363bbc1269a22ffd4cb1ecaeee7a59

**Md5sum:**  af0d232900215f84aa4fb163f17fdc7d

**Description:** Whonix-Gateway Shared Packages
 A metapackage, which installs packages, for a Whonix-Default-Gateway.
 .
 It is shared between Qubes-Whonix and Non-Qubes-Whonix.
 .
 Feel free to remove if you know what you are doing.



## whonix-gw-network-conf

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



## whonix-host-xfce-kvm-freedom

**Package:** whonix-host-xfce-kvm-freedom

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-host-xfce-kvm-freedom_23.0-1_all.deb

**Size:**  63

**Sha256:**  6706ca15a072c03830ec4f3bec8e6d6e81d1e59fb5219e40def21be35c821589

**Sha1:**  5e81ed9748ce059b44fa6cbb9e257387b50d22e7

**Md5sum:**  3b96cfc6b9ca93cb52256a4b3d71549e

**Description:** Whonix Host packages for Freedom Hardware Design
 Designed to run on hardware with Freedom Hardware Design.
 .
 Do not remove.



## whonix-shared-default-applications-gui

**Package:** whonix-shared-default-applications-gui

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-shared-default-applications-gui_23.0-1_all.deb

**Size:**  63

**Sha256:**  293033969ce36d20655bd7cbc9ea1fc59568cbc85221f6c1ead5c8c43ff2d945

**Sha1:**  635be97418c84e46524817217bc01c2d88c93190

**Md5sum:**  102c4baf31650ef8b38547dc956fbb8b

**Description:** Recommended packages for Whonix-Gateway and Whonix-Workstation GUI
 A metapackage, which installs recommended graphical user interface (GUI)
 default applications, which are useful in a default installation of a
 Whonix-Gateway or Whonix-Workstation desktop.
 .
 Safe to remove, if you know what you are doing.



## whonix-shared-packages-dependencies-cli

**Package:** whonix-shared-packages-dependencies-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-shared-packages-dependencies-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  7952ca674217fb856751d3590cb367032d6051d1faebd98130f2e3a5a230651b

**Sha1:**  253499b86b87d54a8eed772a2bebe03285122a9a

**Md5sum:**  5ae4a873d94b0bd705a4c396f7175857

**Description:** Dependencies for Whonix-Gateway and Whonix-Workstation CLI
 A metapackage, which installs packages which both, Whonix-Gateway
 and Whonix-Workstation, depend on.
 .
 Do not remove.



## whonix-shared-packages-recommended-cli

**Package:** whonix-shared-packages-recommended-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-shared-packages-recommended-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  ed90498d2c7aa972b5cd59917a33f0c70f56454412a766f8df81220ff340186b

**Sha1:**  d87017173bf5c52c3dd32a5d7ead3d648defd531

**Md5sum:**  00b4eeb9f45bd723c64e07b0522dc7b4

**Description:** Recommended packages for Whonix-Gateway and Whonix-Workstation CLI
 A metapackage, which includes recommended packages to ensure, Whonix
 standard tools are available and other useful recommended packages.
 .
 Safe to remove, if you know what you are doing.



## whonix-welcome-page

**Package:** whonix-welcome-page

**Version:** 3:5.3-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  855

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/whonix-welcome-page](https://github.com/Whonix/whonix-welcome-page)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/w/whonix-welcome-page/whonix-welcome-page_5.3-1_all.deb

**Size:**  855

**Sha256:**  b19d55b329ec11e16fedc8b871d08cd5948dcf610e71c78df3f51d5c03c971fd

**Sha1:**  e049834fb31c2c7cbb46ebf19df056ebab529e7a

**Md5sum:**  397c61a3d3219cd3e98e195a6d93f2d5

**Description:** Local Browser Homepage for Whonix
 Whonix specific browser homepage used in Tor Browser.
 .
 Contains Whonix logo and Whonix links.
 .
 Safe to remove, if you know what you are doing.



## whonix-workstation-packages-dependencies-cli

**Package:** whonix-workstation-packages-dependencies-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-workstation-packages-dependencies-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  f3b818d65b835663259ea8e0fa8ab3c677e909a5c23552d2b6c06d8c92122681

**Sha1:**  772434a7b1e641a6f3571770057c407c3e300213

**Md5sum:**  977051c24b7664c6864ce9fb81f7ac07

**Description:** Dependencies for Whonix-Workstation CLI
 A metapackage, which installs packages which Whonix-Workstation
 depends on.
 .
 Do not remove.



## whonix-workstation-packages-dependencies-pre

**Package:** whonix-workstation-packages-dependencies-pre

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-workstation-packages-dependencies-pre_23.0-1_all.deb

**Size:**  63

**Sha256:**  a248b3731a3aab9719a0623c602990d424105955fd53a71a21ffeab0c818c3d8

**Sha1:**  c579606434e6c572f4e871eb7849391fc35e85b1

**Md5sum:**  62d7e72447dc0d5fc49c3f66103f769e

**Description:** Dependencies for Whonix-Workstation that changes network related files
 A metapackage, which installs packages which Whonix-Workstation
 depends on. Can not be merged into whonix-workstation-packages-dependencies
 due to conflicts with chroot build process.
 .
 Do not remove.



## whonix-workstation-packages-recommended-cli

**Package:** whonix-workstation-packages-recommended-cli

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-workstation-packages-recommended-cli_23.0-1_all.deb

**Size:**  63

**Sha256:**  3720eb7f252642a88de907cc090f7a0a1d69c864c8b5f325d5467f5de9acb47d

**Sha1:**  844b5153ec2ed791eef7be781cba3e14a75030d2

**Md5sum:**  b843aaceca501984295482e174e53baf

**Description:** Recommended packages for Whonix-Workstation CLI
 A metapackage, which installs packages, which are recommended for
 command line interface (CLI) Whonix-Workstation, because they are
 useful for a Tor Workstation.
 .
 Feel free to remove if you know what you are doing.



## whonix-workstation-packages-recommended-gui

**Package:** whonix-workstation-packages-recommended-gui

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-workstation-packages-recommended-gui_23.0-1_all.deb

**Size:**  63

**Sha256:**  829275b9de668d42577c7053313cf2e7351e02aff9890073289a29c21984dcf0

**Sha1:**  c23cf4aa75999818bfd6fdb0ee684ab361e945f5

**Md5sum:**  f7216d6103c505b472824fffa24b7659

**Description:** Recommended packages for Whonix-Workstation GUI
 A metapackage, which installs packages, which are recommended for
 graphical user interface (GUI) Whonix-Workstation, because they are
 useful for a Tor Workstation.
 .
 Feel free to remove if you know what you are doing.



## whonix-workstation-shared-packages-shared-meta

**Package:** whonix-workstation-shared-packages-shared-meta

**Version:** 3:23.0-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  63

**Recommends:**  

**Conficts:**  

**Replaces:**  

**Provides:**  

**Homepage:**  [https://github.com/Whonix/anon-meta-packages](https://github.com/Whonix/anon-meta-packages)

**Priority:**  optional

**Section:** metapackages

**Filename:**  pool/main/a/anon-meta-packages/whonix-workstation-shared-packages-shared-meta_23.0-1_all.deb

**Size:**  63

**Sha256:**  7cca4bb91ba0132b0ca08a0d643c37be691a36ccad9b4d19bcc4f25c3dc5325f

**Sha1:**  f4f59423411a472d1b7015ed49441e9795c4bb27

**Md5sum:**  b760adfb26cda96239a921951dc23a69

**Description:** Whonix-Workstation Shared Packages
 A metapackage, which installs packages, for a Whonix-Default-Workstation.
 .
 It is shared between Qubes-Whonix and Non-Qubes-Whonix.
 .
 Feel free to remove if you know what you are doing.



## whonix-ws-network-conf

**Package:** whonix-ws-network-conf

**Version:** 3:3.7-1

**Architecture:**  all

**Maintainer:**  Patrick Schleizer <adrelanos@whonix.org>

**Installed_size:**  41

**Recommends:**  

**Conficts:**  diverts-etc++resolv.conf

**Replaces:**  anon-ws-dns-conf, kicksecure-network-conf

**Provides:**  diverts-etc++resolv.conf

**Homepage:**  [https://github.com/Whonix/whonix-ws-network-conf](https://github.com/Whonix/whonix-ws-network-conf)

**Priority:**  optional

**Section:** misc

**Filename:**  pool/main/w/whonix-ws-network-conf/whonix-ws-network-conf_3.7-1_all.deb

**Size:**  41

**Sha256:**  946b032b3fa946d4208e5708bcfb2e090eefe136b16c76c5ed56fbb29401cbc1

**Sha1:**  03161277188e99d7f7e6b19f903ff6d2257020bc

**Md5sum:**  2fccd8d18e12f0ee5c9b365b22774ef8

**Description:** Network Configuration for Whonix-Workstation
 Includes /etc/network/interfaces for Whonix-Workstation.
 .
 Sets up an internal network interface eth0.
 .
 DNS configuration Anonymity Linux Distribution Workstations
 Whether a Anonymity Linux Distribution Gateway supports anonymized system DNS
 for Workstation's traffic (also known as Transparent DNS Proxy) mainly depends
 on the Gateway's firewall.
 .
 This package is simply installing /etc/resolv.conf which points to
 10.152.152.10, where an Anon-Gateway is supposed to provide a DnsPort on port
 53. IP HARDCODED but no need to change because only description.
 .
 Currently relevant for Non-Qubes-Whonix only.



