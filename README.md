<div align="center">

# 🗂️ Flipper Zero File Dump  
### Personal Configuration & Active File Set

</div>

---

## ⚖️ Educational Use & Responsibility Notice

This repository contains a dump of the files currently used on my Flipper Zero device.  
It is shared strictly for **educational, research, and configuration reference purposes**.

All files are intended for use on hardware you personally own or have explicit permission to test.  
I do not condone or endorse misuse, unauthorized access, interference with devices, or any form of skidding.

You are fully responsible for how you use the contents of this repository.

---

## 📦 Overview

This repository contains my **active Flipper Zero file collection**, including configurations, captures, and supported file types currently deployed on my device.

It serves as:

- A structured backup of my working environment  
- A reference for configuration setup  
- A learning resource for understanding file organization  
- A baseline for firmware-based experimentation  

---

## 💾 SD Card Storage Information

The Flipper Zero stores user files on the **microSD card**, which acts as the device’s primary storage layer.

Key notes:

- All user files (Sub-GHz, IR, NFC, iButton, etc.) are stored within the `root` directory.
- Organization typically follows structured folders such as:
  - `subghz/`
  - `infrared/`
  - `nfc/`
  - `ibutton/`
  - `badusb/`
- Proper folder structure ensures the firmware recognizes and loads files correctly.
- Regular backups of the SD card are recommended to prevent data loss.
- Use high-quality microSD cards formatted to FAT32 for stability and compatibility.

Maintaining a clean, organized SD structure improves performance and reduces file conflicts.

---

## 🚀 Firmware

This device is running **Momentum Firmware**:

🔗 https://momentum-fw.dev/

Momentum provides extended functionality, expanded protocol support, and additional customization features beyond stock firmware.  
All files in this repository are structured for compatibility with Momentum firmware unless otherwise stated.

---

## 🛠 Requirements

- Flipper Zero  
- microSD card (FAT32 formatted recommended)  
- Momentum Firmware (recommended)

---

## 🤝 Usage & Reference

This repository is intended as a reference configuration and educational archive.  
If adapting these files for your own setup:

- Verify compatibility with your firmware version  
- Confirm regional frequency regulations where applicable  
- Keep backups before modifying your device  

---

<div align="center">

</div>
