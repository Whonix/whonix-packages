---
layout: default
title: vm-config-dist
nav_order: 232
parent: binary-sparc
grand_parent: bullseye-proposed-updates main
---

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


