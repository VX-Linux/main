# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/vx-5.1-desktop.jpg" style="width:960px;border-radius:10px!important;">

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

**Aliases**
- **install** pkg = sudo xbps-install -Su pkg
- **query** pkg = sudo xbps-query -Rs pkg
- **remove** pkg = sudo xbps-remove -Ro pkg
- **logout** = loginctl terminate-user $USER
- **services** = sudo vsv

**Update Notifier**
- When logging in you will be notified if new package updates are available. Update to remove the "nag" or ignore it to let updates build up. Remove "Notifier" from Autostart to remove the check.

**Sudo Password**
- Sudo password is disabled to make setup & daily management more convenient for the user. To disable this delete /etc/sudoers.d/wheel. 

**Login**
- anon / live

**Things to do before installing to disk**
- Remove any firmware / packages you don't need and run Cleanup to remove leftovers
- Avoid installing large / many software as you will likely run out of (live-session) space
- Run Services to configure your startup services
- Run Update to download VX dependencies and be fully up-to-date

**Installation**
- Open a terminal and run <code>vxinstaller</code>

**Issues and Suggestions**
- If you use VX and have issues or suggestions to make it better please use the <a href="https://github.com/VX-Linux/main/issues">Issues</a> section

**Known Issues**
- Desktop not displayed on secondary monitor/s
- When changing system font size Yad dialogs do not follow suit<br>- Enter home folder and run sudo cp -r .config/gtk* /root/.config
- Transmission references anon in settings<br>- sed -i "s/anon/YOURUSERNAME/g" /home/YOURUSERNAME/.config/transmission/settings.json

**Roadmap**
- <a href="https://vxlinux.org/roadmap/">Roadmap</a>

**Updates 5.3**
* Add selective options to cleanup
* Fix clamav installer
* Standardardise font sizes across desktop, terminal, etc
* Update Chrome installer to remove extra apps now installed by google
* Update Virtualbox script to newer extension pack (7.0.10)

