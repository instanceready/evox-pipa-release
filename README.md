# Evolution X builds for Xiaomi Pad 6

![EvoX Logo](https://i.imgur.com/1vesDCw.jpeg)

> **NOTES:</br>This ROM is provided as-is with no warranty. Use at your own risk.**
> **</br>HyperOS 2 Global Firmware is already included in ROM**


## Installation Guide

### Installing Evo X for the first time (Clean Flash)

<details>
<summary>Click to expand installation steps</summary>

1. Download the ROM package along with boot, dtbo and vendor_boot (links mentioned in post)
2. Put downloaded files in a folder (your platform tools folder preferred)
3. Reboot to bootloader (hold power + volume down button)
4. In your PC, open terminal where you copied the above files and run the following commands:

```bash
fastboot flash boot boot.img
fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
fastboot reboot recovery
```

5. Format data via recovery (optional if flashing on the same ROM)
6. Select "Reboot to recovery" (Advanced → Reboot to recovery)
7. Select "Apply update" in recovery
8. In your PC terminal, run `adb sideload rom.zip` (replace rom.zip with the downloaded ROM package name)
9. If you are flashing a vanilla build and want to flash GApps, select "Reboot to recovery" (installation ends at 47% displayed on your PC terminal) and then sideload GApps by selecting "Apply update". Skip this step if you are already flashing a GApps build
10. Reboot to system
</details>

### Updating from an existing Evo X build

<details>
<summary>Click to expand update steps</summary>

1. Select "Reboot to recovery" (Advanced → Reboot to recovery)
2. Select "Apply update" in recovery
3. In your PC terminal, run `adb sideload rom.zip` (replace rom.zip with the downloaded ROM package name)
4. If you are flashing a vanilla build and want to flash GApps, select "Reboot to recovery" (installation ends at 47% displayed on your PC terminal) and then sideload GApps by selecting "Apply update". Skip this step if you are already flashing a GApps build
5. Reboot to system
</details>

## Features

- Based on Android 15
- Pre-rooted with KernelSU-Next (just install the app to use it)
- HyperOS 2 Global Firmware included
- Optimized performance and battery life
- Enhanced multimedia experience

## Changelog
<details>
<summary><b>April 16, 2025</b></summary>

- Initial Build

</details>

##


## Useful Links

- [Google Apps for Android 15](https://github.com/MindTheGapps/15.0.0-arm64/releases)
- [KernelSU-Next](https://github.com/KernelSU-Next/KernelSU-Next/releases)
- [Xiaomi Pad 6 XDA Thread](https://forum.xda-developers.com/f/xiaomi-pad-6.12659/)

---

### Known Issues

- None reported yet
