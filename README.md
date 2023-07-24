# VX Linux
<img src="https://github.com/VX-Linux/main/blob/main/vx-5.0-menu.jpg" style="width:960px;border-radius:10px!important;">

**Features**
- Light, highly-optimised base
- Automatic configuration for bluetooth hardware, display graphics (ATI and Intel), laptops and SSD drives
- Basic software set, minimal theming, no bloat, no bling bling
- Uses the default Void repos
- BIOS and UEFI compatible

**NEW: Overhauled Tools**
- Accessibility: Enable brltty and/or espeakup
- Appmaker: Create apps for your favourite online activities
- Autoconfigure: Setup your hardware and remove unneeded packages
- Backup: Backup your entire installation (single file system only)
- Cleanup: Empty trash and package cache, remove unused kernels and packages
- Mirrors: Select and activate custom mirrors (Fastly CDN is the default)
- Timezone: Automatically set timezone to current location
- Update VX: Update all VX files, scripts and utilities, along with any bugfixes for issues reported by users

**Theming**
- If you prefer a stock standard Plasma desktop then open a terminal and run <b><code>sudo defaultkde</code></b> and logout. Similarly run <b><code>sudo defaultvx</code></b> to revert to VX defaults. Note: For fresh installation, backup your dotfiles if you've made customisations.

**Update Notifier**
- When logging in you will be notified if new package updates are available. Update to remove the "nag" or ignore it to let updates build up. Remove "Notifier" from Autostart to remove the check.

**Sudo Password**
- Sudo password is disabled to make setup & daily management more convenient for the user. To disable this delete /etc/sudoers.d/wheel.

**Login**
- anon / live

**Things to do once connected (if not already connected when first logging in)**
- Run Timezone to update to current location
- Run Update to be fully up-to-date before installing

**Installation**
- Open a terminal and run <code>vxinstaller</code>

**Issues and Suggestions**
- If you use VX and have issues or suggestions to make it better please use the <a href="https://github.com/VX-Linux/main/issues">Issues</a> section

**Known Issues**
- Appmaker does not work in live session - connect to internet and run Menu > Update to complete the setup. Most VX utilities require an active and stable internet connection to function correctly.
- Backup incorrectly reports estimated backup size by 2x

<a href="https://vxlinux.org/roadmap/">Roadmap</a>
