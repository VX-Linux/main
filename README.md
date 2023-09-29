# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/preview.jpg" style="width:960px;border-radius:10px!important;">
<img src="https://github.com/VX-Linux/main/blob/main/vx-layouts.png" style="width:960px;border-radius:10px!important;">

**Features**
- Appmaker: Create apps for your favourite online activities
- Automatic configuration for bluetooth hardware, display graphics (ATI and Intel), laptops and SSD drives
- BIOS and UEFI compatible
- Browser Manager: Install/uninstall popular browsers (Brave, Chrome, Chromium, Edge, Falkon, Firefox, Opera, Pale Moon, Vivaldi, Waterfox)
- Layouts: (Pictured above) Several layouts to suit your workflow (Default Plasma, Elementary, Mac, MX, VX6, Win7, Win10, Win11)
- Light, highly-optimised base
- Light software set, minimal theming, no bloat, no bling bling
- Service Manager: Enable/disable services
- Uses the default Void repos

**VX Tools**
- Backup: Backup your entire installation (single file system only)<br>- Alt-F2 > <code>sudo backupvx</code>. Saved to /bak
- Cleanup: Empty trash and package cache, remove unused kernels and packages<br>- Alt-F2 > <code>sudo cleanvx</code>
- Sync: Automatically set timezone to current location<br>- Alt-F2 > <code>sudo syncvx</code>
- Update: Update all VX files, scripts and utilities<br>- Alt-F2 > <code>sudo updatevx</code>

**Update Notifier**
- When logging in you will be notified if new package updates are available. Update to remove the "nag" or ignore it to let updates build up. Remove "Notifier" from Autostart to remove the check.

**Sudo Password**
- Sudo password is disabled to make setup & daily management more convenient. 

**Login**
- anon / live

**Things to do before installing to disk**
- Set your custom keyboard and language
- Run Service Manager to configure your startup services
- Run Appmaker once so it's activated and available after installation
- Avoid installing large / many software as you will likely run out of (live-session) space
- Update VX

**Deb / Rpm Installer**
- Double-click the deb/rpm file to install in terminal

**Flatpak Installer**
- Double-click the flatpakref file to install in terminal

**Updates arriving in v6.0**
- All installers updated (most have been updated to download the latest release)
- Browser manager
- ISO built with new updated mklive
- Layout switcher
- Unused kernels added to Cleanup
