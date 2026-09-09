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


### Latest Update (v1.5)
* **Pre-installed BORE Kernel & Updater:** Includes the BORE CPU scheduler kernel (selectable via GRUB boot menu post-installation for safety).
* **Desktop Updater Script:** Pre-integrated desktop tool for one-click BORE kernel updates.
* **Known Issue:** The updater script icon may appear twice on the desktop. This cosmetic issue will be resolved in the next update.


### Download Live-ISO
* [Download YaniOS-V1.5.iso on Google Drive](https://drive.google.com/file/d/1p20aIDuIO9uRKB7QxkKVV196U0VuxCLu/view?usp=drive_link)
### ISO Verification
* **SHA256:** `61ed5d9ed272685d26c85d4159e3dac889e5cd9d7021e6a9893195b033b8f062`

### Futur Update Version 1.6
* The **BORE kernel** is being removed in the future version for security reasons.
The script for building the kernel remains, anyone who wants it can compile it themselves.
The standard boot kernel for the live ISO remains the XanMod Kernel 7.X.X.

### Exercise caution when building the kernel
* I assume no liability or warranty regarding your hardware,
as this is still a personal backup rather than a Linux distribution. I am sharing it simply because
I love and live by open-source principles.



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
