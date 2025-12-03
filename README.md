# Ventoy-USB-es - README

## Introduction
[Ventoy](https://www.ventoy.net/en/index.html) is an open-source tool for creating bootable USB drives for ISO/WIM/IMG/VHD(x)/EFI files, allowing multiple images on a single drive.
This repository aims to establish an initial, general, and structured configuration based on the Spanish language (Spain).

The aliases and icons for most ISOs are established, as well as their organization into directories (Windows, Linux, Utilities).

It contains an **autounattend.xml*** for **Windows 10-11**
- Spanish language and region.
- ByPass for Windows 11.
- Automation of most of the installation, except for the Windows serial number request (post-installation activation), computer name, user (local), password, and disk partitioning.
- Removal of most pre-installed Windows bloatware, leaving only the most basic.
- A dark theme with a gray background and taskbar configuration is set.

It also includes a registry file to restore the classic Windows **Image Viewer** and instructions for placing the **Recycle Bin** on the taskbar.

## Structure
```
├─ 📂 Apps
├─ 📂 Docs
├─ 📂 drivers
|
├─ 📂 ISO
|  ├─ 📂 1-Windows
|  ├─ 📂 2-Linux
|  └─ 📂 3-Utility
|
├─ 📂 persistence
|
└ 📂 ventoy/
  ├─ {} ventoy.json
  ├─ 🖹 README.md
  ├─ 📂 script/
  |	  └─ 📂 W10-11_autounattend_v1
  └─ 📂 theme/
	  └─ 📂 poly-dark/
		  └─ 📂 icons
```

## Theme
The theme is [Poly-Dark](https://github.com/shvchk/poly-dark) with a custom gray background and some added icons.

## Images
- **Windows**
- **Linux**
	- [Arch](https://archlinux.org/)
	- [Debian](https://www.debian.org/)
	- [Fedora](https://fedoraproject.org/)
	- [Gentoo](https://www.gentoo.org/)
	- [OpenSUSE](https://www.opensuse.org/)
	- [Manjaro](https://manjaro.org/)
	- [Linux Mint](https://linuxmint.com/)
	- [Ubuntu](https://ubuntu.com/)
	- [Kali-Linux](https://www.kali.org/)
- **Utilities**
	- [Acronis True Image](https://www.acronis.com/es/products/true-image/)
	- [CloneZilla](https://clonezilla.org/)
	- [HirensBootCD](https://www.hirensbootcd.org/)
	- [Gparted](https://gparted.org/index.php)
	- [Memtest86](https://www.memtest86.com/)
	- [Parted Magic](https://partedmagic.com/)
	- [Rescatux](https://www.supergrubdisk.org/rescatux/)
	- [System Rescue](https://www.system-rescue.org/)
	- [Virtio Win Drivers](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/)
	- [WinPE Sergei Strelec](https://sergeistrelec.name/winpe-10-8-sergei-strelec-english/)
