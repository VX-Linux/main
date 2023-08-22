# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/preview.jpg" style="width:960px;border-radius:10px!important;">

**Features**
- Light, highly-optimised base
- Automatic configuration for bluetooth hardware, display graphics (ATI and Intel), laptops and SSD drives
- Basic software set, minimal theming, no bloat, no bling bling
- Uses the default Void repos
- BIOS and UEFI compatible

**NEW: Overhauled Tools**
- Appmaker: Create apps for your favourite online activities
- Backup: Backup your entire installation (single file system only)
- Cleanup: Empty trash and package cache, remove unused kernels and packages
- Default: Replace VX layout with a default Plasma desktop
- Services: Enable / disable service
- Timezone: Automatically set timezone to current location
- Update: Update all VX files, scripts and utilities, along with any bugfixes for issues reported by users
- Xmirror: Select and activate custom mirrors (Fastly CDN is the default)

**Update Notifier**
- When logging in you will be notified if new package updates are available. Update to remove the "nag" or ignore it to let updates build up. Remove "Notifier" from Autostart to remove the check.

**Sudo Password**
- Sudo password is disabled to make setup & daily management more convenient for the user. To disable this delete /etc/sudoers.d/wheel. 

**Login**
- anon / live

**Things to do before installing to disk**
- Avoid installing large / many software as you will likely run out of (live-session) space
- Run Services to configure your startup services
- Run Update to download VX dependencies and be fully up-to-date

**Installation**
- Open a terminal and run <code>vxinstaller</code>

**Issues and Suggestions**
- If you use VX and have issues or suggestions to make it better please use the <a href="https://github.com/VX-Linux/main/issues">Issues</a> section

**Wayland Disabled by Default**
- To restore wayland session option<br><code>sed -i "s/NoDisplay=true//g" /usr/share/wayland-sessions/plasmawayland.desktop</code>

**Deb / Rpm Installer**
- This is already included - right-click on the file and select Install DEB or Install RPM.
