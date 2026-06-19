# Pixel 7 to 9 Series Patched init_boot Files

Welcome! This repository contains Magisk-patched `init_boot` files for the Google Pixel 7, 8, and 9 series. You can use these files to easily root your device. 

## Supported Devices
* **Pixel 7 Series:** Pixel 7 (panther), Pixel 7 Pro (cheetah), Pixel 7a (lynx)
* **Pixel 8 Series:** Pixel 8 (shiba), Pixel 8 Pro (husky), Pixel 8a (akita)
* **Pixel 9 Series:** Pixel 9 (tokay), Pixel 9 Pro (caiman), Pixel 9 Pro XL (komodo), Pixel 9 Pro Fold (comet), Pixel 9a (tegu)

## Requirements
* An Unlocked Bootloader.
* Android SDK Platform-Tools (ADB & Fastboot) installed on your computer.

## How to Root (Instructions)

**Step 1: Download Files**
Download the patched `init_boot` image for your specific phone model from this repository. Also, download the `Magisk-v30.7.apk` included here.

**Step 2: Enter Fastboot Mode**
Turn off your phone. Turn it on by holding the **Power** and **Volume Down** buttons together until you see the Fastboot Mode screen. Connect your phone to your computer with a USB cable.

**Step 3: Flash the Patched File**
Open your computer terminal or command prompt. Type the following command and press Enter:
```bash
fastboot flash init_boot <drag_and_drop_your_downloaded_image_file_here>
```
**Step 4: Reboot**
After the flashing is done, type this command to restart your phone:

```bash
fastboot reboot
```
**Step 5: Install Magisk App**
Once your phone turns on normally, install the Magisk-v30.7.apk file. Open the Magisk app. If it asks to complete an extra setup, allow it and reboot one last time.

You are fully rooted!

Disclaimer: Rooting your device is your own responsibility. Always make sure to use the exact file that matches your device model to avoid bootloops.

