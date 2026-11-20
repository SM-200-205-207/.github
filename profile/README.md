# Samsung Galaxy Tab A8 Project (SM-X200 / SM-X205 / SM-X207)

Unified open-source custom Android bringup for the Samsung Galaxy Tab A8 10.5" family (Unisoc Tiger T618 / `ums512`).

---

> [!WARNING]
> ### Experimental & Work In Progress (WIP)
> All repositories and branches hosted within this organization are currently in an active bringup and experimental development phase.
> - Unless you are an experienced ROM developer or know what you are doing, **do not expect a fully functional ROM or daily-driver stability** by compiling this source code.
> - Inquiries related to *"how to build"*, *"ETAs"*, or general user-support questions will be marked as off-topic and ignored.
> - Pull requests, bug fixes, and issues accompanied by actionable logs (`dmesg`, `logcat`, `pstore`) are always welcome.

> [!CAUTION]
> ### Bootloader & Warranty Notice
> Unlocking the bootloader on Samsung devices permanently trips Knox warranty status (`0x1`) and erases all userdata. Modifying boot images or dynamic partition tables can lead to soft-bricks if flashing procedures are not properly followed. Flash and test at your own risk.

---

## Supported & Target Devices

| Device Codename | Model | Connectivity | Platform / SoC | Status |
| :--- | :--- | :--- | :--- | :--- |
| **`gta8wifi`** | SM-X200 | Wi-Fi Only | Unisoc Tiger T618 (`ums512`) | **In Active Bringup (A14)** |
| **`gta8lte`** | SM-X205 | LTE / Wi-Fi | Unisoc Tiger T618 (`ums512`) | Planned |
| **`gta8`** | SM-X207 | Cellular / Wi-Fi | Unisoc Tiger T618 (`ums512`) | Planned |

---

## Core Repositories

* [**android_device_samsung_gta8wifi**](https://github.com/SM-200-205-207/android_device_samsung_gta8wifi): Device tree configuration, init scripts, and audio/VINTF policies.
* [**android-kernel-smx200-gta8wifi**](https://github.com/SM-200-205-207/android-kernel-smx200-gta8wifi): Linux kernel source (4.14.x) patched for Android 14 AOSP/LineageOS bringup.
* [**proprietory-vendor-smx200-gta8wifi**](https://github.com/SM-200-205-207/proprietory-vendor-smx200-gta8wifi): Extracted and cleaned vendor prebuilts, firmware, and HALs.

---

## Contributions

If you would like to help bring up or test features (RIL on LTE models, camera, audio, or graphics), please fork the respective repositories and submit a Pull Request.
