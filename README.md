# YaniOS
Personal Gaming Distro Backup (Based on MX Linux 25 / KDE Plasma 6 / AMD optimized)

# YaniOS - Personal Gaming Distro Backup

An optimized, Based on MX Linux 25 / KDE Plasma 6 based gaming Linux for AMD Zen 3 & AMD GPUs.


### Key Modifications & Features
* **Bloatware Removed:** Stripped down for maximum performance (Removed LibreOffice, Conky, Strawberry, Okular, Yakuake, Gwenview, etc.).
* **Gaming Ready:** Pre-installed Steam, Steam Devices, Heroic Games Launcher, and GameMode.
* **Kernel & Graphics:** Powered by XanMod Kernel + LTS Backup Kernel and modern Mesa 26.x drivers.
* **Lightweight Apps:** Replaced heavy default apps with lightweight alternatives (Haruna Video Player, qimgv Image Viewer).
* **Codecs:** Pre-configured with full multimedia and WebP support out of the box.


### Latest Update (v1.6)
**Bore kernel system removed:** 
* The entire Bore kernel system, including its associated updater, has been completely removed from the project to streamline the codebase and system maintenance.

**Default kernel updated:**
* Linux 7.2.4-x64v3-xanmod1 now serves as the primary default kernel integrated and active even within the live ISO to ensure maximum performance on AMD architecture.

**Fallback kernel:** 
* Linux-image-7.1.8-1mx25ahs-siduction is now firmly configured in the bootloader as a robust, modern fallback option.


### Download Live-ISO
* [Download YaniOS-1.6.iso on Google Drive](https://drive.google.com/file/d/1p20aIDuIO9uRKB7QxkKVV196U0VuxCLu/view?usp=drive_link)
### ISO Verification
* **SHA256:** `9c2d47f7a9210d57ae5514dc59440e63653f538b6ee23280989a7767a722f504`
* **MD5:** `7b4d948f12ac1e20a2e75ef9f7b8dfd3`


----------
### Disclaimer & Support
> **CRITICAL INSTALLATION REQUIREMENT:** 
> **Must be installed using SYSTEMD only! Do not use SysVinit.**
>
> This is a purely private system backup built for personal use. No support, no guarantees, and no bug fixes provided.
> Nvidia GPUs are completely unsupported and untested. Use at your own risk.


----------
### Credits
About MX Linux

YaniOS does not hide its origins.
YaniOS is based on MX Linux 25, which itself is based on Debian.
MX Linux tools, components, branding, and installation infrastructure may therefore remain visible within the system and installation process.
The YaniOS branding and customization are my own work, the underlying MX Linux and Debian projects deserve their respective credit.
