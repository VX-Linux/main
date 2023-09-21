# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/preview.jpg" style="width:960px;border-radius:10px!important;">

**Features**
- Light, highly-optimised base
- Automatic configuration for bluetooth hardware, display graphics (ATI and Intel), laptops and SSD drives
- Light software set, minimal theming, no bloat, no bling bling
- Uses the default Void repos
- BIOS and UEFI compatible

**NEW: Overhauled Tools**
- Appmaker: Create apps for your favourite online activities
- Backup: Backup your entire installation (single file system only)<br>- Open a terminal and run <code>sudo backupvx</code>. Saved to /bak
- Browser Manager: Install/uninstall popular browsers<br>(Brave, Chrome, Chromium, Edge, Falkon, Firefox, Pale Moon, Tor, Vivaldi, Waterfox)
- Cleanup: Empty trash and package cache, remove unused kernels and packages<br>- Alt-F2 > <code>sudo cleanvx</code>
- Layout: Choose between several layouts (Default Plasma, Elementary, Macish, MXish, Win7, Win11)
- Services: Enable/disable services
- Sync: Automatically set timezone to current location<br>- Alt-F2 > <code>sudo syncvx</code>
- Update: Full system update and update all VX files, scripts and utilities
- Xmirror: Select and activate custom mirrors (Fastly CDN is the default)<br>- Open a terminal and run <code>sudo xmirror</code>

**Update Notifier**
- When logging in you will be notified if new package updates are available. Update to remove the "nag" or ignore it to let updates build up. Remove "Notifier" from Autostart to remove the check.

**Sudo Password**
- Sudo password is disabled to make setup & daily management more convenient and so you don't have to enter your password dozens of times a day even though you've already authenticated yourself by correct login... To disable this delete /etc/sudoers.d/wheel. 

**Login**
- anon / live

**Things to do before installing to disk**
- Avoid installing large / many software as you will likely run out of (live-session) space
- Run Services to configure your startup services
- Run Update to download VX updates and be fully up-to-date

**Wayland session hidden by default**
- To restore wayland session option open a terminal and run <code><b>sudo enable-wayland</b></code> and logout. The Wayland session will now be available.

**Deb / Rpm Installer**
- Right-click on the file and select Install DEB or Install RPM.

**Updates arriving in v6.0**
- Browser manager
- Layout switcher
- Unused kernels added to Cleanup
- Wayland session is default in preparation for upcoming Plasma 6.0
