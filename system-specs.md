# 💻 Sony VAIO SVE1513ACNB - System Specifications & Hardware Report

A complete technical specification, hardware inventory, and upgrade roadmap report for the **Sony VAIO E-Series (SVE1513ACNB)** laptop running Windows 10.

---

## 📌 1. System Overview

| Parameter | Specification Details |
| :--- | :--- |
| **Device Model** | Sony VAIO SVE1513ACNB |
| **Manufacturer** | Sony Corporation |
| **System Type** | x64-based PC |
| **Host Name** | `DESKTOP-IIE0RCM` |
| **BIOS Version** | Insyde Corp. R0170D5 (Release: 14-Nov-2012) |
| **Power State** | Direct AC Adapter (Battery Depleted/Bypassed) |

---

## ⚙️ 2. Hardware Specifications

### 🧠 Processor (CPU)
* **Model:** Intel(R) Core(TM) i3-2328M (Sandy Bridge, 2nd Gen)
* **Cores / Threads:** 2 Physical Cores / 4 Logical Processors
* **Base Clock:** 2.20 GHz (Locked - Non-Turbo)
* **Socket Type:** Socket G2 (rPGA988B) - *Removable / Upgradeable*
* **Architecture:** 32nm / 35W TDP

### 🎛️ Motherboard & Chipset
* **Chipset Family:** Intel 7-Series / C216 Chipset Family (HM75/HM76 compatible)
* **LPC Controller:** Intel 7-Series Express Chipset LPC Controller
* **Expansion:** 2x SODIMM Slots, 1x SATA III Bay, 1x Optical Bay (SATA)

### 🗄️ Memory (RAM)
* **Installed RAM:** 10.00 GB DDR3 SODIMM
* **Configuration:** Asymmetric Dual Channel / Flex Mode
  * **Slot 1 (`SODIMM1`):** 2 GB DDR3
  * **Slot 2 (`SODIMM2`):** 8 GB DDR3
* **Memory Status:** ~4.8 GB Free under standard load

### 🎮 Graphics (GPU) & Display
* **GPU Type:** Intel(R) HD Graphics 3000 (Integrated)
* **Driver Version:** 9.17.10.4459
* **Allocated RAM:** ~2.1 GB Dynamic Memory

### 💾 Storage Configuration (Dual Drive Setup)

| Drive | Type | Model | Capacity | Mount / Partition | Free Space |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Disk 0 (Primary)** | SATA SSD | Geonix Gold 128GB | ~120 GB | `C:` (OS Drive) | ~70.5 GB Free |
| **Disk 1 (Secondary)**| SATA HDD | WDC WD5000LPLX-75ZNTT0 | 500 GB | `D:` (Data / Caddy) | ~423 GB Free |

---

## 🌐 3. Network & Connectivity

* **Wireless Adapter (Wi-Fi):** Qualcomm Atheros AR9485WB-EG Wireless Network Adapter (802.11 b/g/n)
* **Ethernet (LAN):** Realtek PCIe GbE Family Controller (Gigabit Ethernet)
* **USB Ports:** Intel 7-Series Enhanced Host Controllers (USB 3.0 / USB 2.0)

---

## 🪟 4. Operating System & Software Environment

* **OS Edition:** Microsoft Windows 10 Home Single Language (64-bit)
* **Version / Build:** 22H2 / Build 19045.x
* **Installation Date:** 07-Dec-2019
* **Boot Environment:** Windows Boot Manager on `\Device\HarddiskVolume1`

---

## 🚀 5. Performance Assessment & Upgrade Roadmap

### ✅ Current Strengths
1. **SSD Boot Drive:** Fast OS responsiveness and quick launch times.
2. **Dual Storage:** Fast 128GB SSD for OS + High capacity 500GB HDD in Optical Caddy for files.
3. **Chipset Compatibility:** Intel 7-Series chipset allows 3rd Gen Ivy Bridge CPU drops without 30-minute thermal/chipset watchdog shutdowns.

### ⚠️ Current Bottlenecks
* **CPU:** Core i3-2328M lacks Intel Turbo Boost (permanently capped at 2.20 GHz).
* **RAM Mismatch:** 2GB + 8GB configuration prevents optimal True Dual-Channel memory throughput.

### 🛠️ Recommended Hardware Upgrades

| Upgrade Component | Recommended Part | Expected Performance Gain |
| :--- | :--- | :--- |
| **CPU Upgrade** | Intel Core i5-3230M / i5-3320M *(3.20 GHz Turbo)* | **+45-55%** CPU boost + Upgrades iGPU to HD 4000 |
| **RAM Symmetry** | Replace 2GB stick with 8GB DDR3L 1600MHz *(16GB Total)* | **+20%** Memory & Graphics Bandwidth (Dual-Channel) |
| **Thermal Servicing** | Fan Clean + Arctic MX-4 Thermal Paste | Eliminates thermal throttling under load |

---

*Report generated on:* `2024`  
*System ID:* `SONY-VAIO-SVE1513ACNB`