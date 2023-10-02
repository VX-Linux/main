# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/vx-6.0.jpg" style="width:960px;border-radius:10px!important;">
<img src="https://github.com/VX-Linux/main/blob/main/vx-layouts.png" style="width:960px;border-radius:10px!important;">

**Features**
- Appmaker: Create apps for your favourite online activities (ensure no spaces in title)
- Automatic configuration for bluetooth hardware, display graphics (ATI and Intel), laptops and SSD drives
- Backup: Backup your entire installation (single file system only)
- Browser Manager: Install/uninstall popular browsers (Brave, Chrome, Chromium, Edge, Falkon, Firefox, Opera, Pale Moon, Vivaldi, Waterfox)
- Cleanup: Empty trash and package cache, remove unused kernels and packages, etc
- Deb / Rpm Installer: Double-click the deb/rpm file to install in terminal
- Flatpak Installer: Double-click the flatpakref file to install in terminal
- Layouts: (Pictured above) Several layouts to suit your workflow (Default Plasma, Elementary, Mac, MX, VX6, Win7, Win10, Win11)
- Light, highly-optimised base
- Light software set, minimal theming, no bloat, no bling bling
- Service Manager: Enable/disable services
- Sync: Automatically set timezone to current location
- Update: Update all VX files, scripts and utilities
- BIOS and UEFI compatible
- Uses the default Void repos

**Helper Scripts (run as root)**
- activate-bluetooth / deactivate-bluetooth
- disable-wayland: Hide wayland session from login screen to get a cleaner look if only using X11 (enable-wayland to revert)
- disable-xsession: Hide X11 session from login screen to get a cleaner look if only using Wayland (enable-xsession to revert)
- installers: Setup scripts for 3rd-party software (/usr/share/vx/installers - right-click and select Run as Root)
- set-default-layout: Set preferred layout for all new users (users can still change their layout after this is set)

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

**Credits**
<br>
The Void Team<br>
https://voidlinux.org

KDE Plasma<br>
https://kde.org/plasma-desktop/

Users for testing and providing valuable feedback<br>
Special thanks to Daz

Plasmoids<br>
Avalon Plasmoid - adhe, Minimal Menu - Juha Nuutinen, kppleMenu - Kpple.org, OnzeMenu 11 - adhe, Run Command - Himprakash Deka, Simple 10 Menu - Fauzie Rofi
