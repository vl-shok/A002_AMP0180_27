# 📡 A002_AMP0180_27 RF Power Amplifier Project – Full Hardware Package

This repository contains the complete production, enclosure, and reference files for the **A002 Wideband RF Power Amplifier** (0.1–8000 MHz, 0.5W), intended for laboratory use, testing, and RF prototyping.

---

## 📁 Project Structure

| Folder / File               | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `/Production files PCB/`    | PCB fabrication package (Gerbers, pick and place, drawing, BOM, and README) |
| `/Production Files Covers/` | CNC-ready and laser marking files for aluminum covers (includes README)     |
| `/Additional files/`        | S-parameters, 3D model, schematic, photos, simulation results               |
| `README_root.md`            | This file                                                                  |

---

## 🛠️ Project Overview

- **Frequency range**: 100 kHz – 8 GHz  
- **Power output**: ~0.5 W (+27 dBm)  
- **Gain**:  
  - 0.1 GHz – 24.1 dB  
  - 1 GHz – 21.4 dB  
  - 5 GHz – 18.4 dB  
  - 8 GHz – 16.4 dB  
  *(see measured S-parameters for full data; actual values may vary slightly depending on temperature and IC spread)*  
- **Noise figure**:  
  - 0.4 GHz – 3.28 dB  
  - 1 GHz – 3.2 dB  
  - 5 GHz – 2.7 dB  
  - 8 GHz – 2.98 dB  
- **Power input**: 9–12 V @ ~159 mA  
- **Internal regulation**: ADP7102ACPZ-R7 LDO (8 V output)  
- **Connectors**:  
  - RF: SMA (vertical mount)  
  - Power: JST B2B-EH-A (2.5 mm pitch), mating connector included  
- **Dimensions (with connectors)**: 15.2 mm × 36.6 mm × 22.9 mm  
- **Weight**: ~21 g  
- **Enclosure**: CNC-machined 6061 aluminum

---

## 🧾 PCB Production Files

Located in: `/Production files PCB/`

Includes:
- `Gerbers.zip` – Complete Gerber and drill files
- `Pick Place for PCB1.csv` – XY file for automated assembly
- `Bill of Materials` – Full component list
- `Drawing.pdf` – Board dimensions
- `README.md` – PCB stackup, specifications, file definitions

📌 Fabricated on FR-4 TG155 (4-layer, 1.2 mm, JLC04121H-1080A)

---

## 🧱 Aluminum Enclosure Covers

Located in: `/Production Files Covers/`

Includes:
- `A002.101.00 AD BOT Cover v1.0.pdf` – Technical drawing with M3 threading
- `A002.101/102 .step` – 3D models for bottom and top covers
- `Title.dxf`, `Reference for lazer.jpg` – For optional laser engraving
- `ReadMe.md` – Machining and engraving notes

---

## 📂 Additional Files

Located in: `/Additional files/`

Includes:
- `S-parameters/` – Touchstone data + plotted results (S11, S21, etc.)
- `PCB1.step` – Full board 3D model
- `Schematic.pdf` – Final schematic
- Assembly photo, labeled port/output views, 3D references

---

## 🛒 Need a Ready-to-Use Version?

If you’d like to save time or need a verified reference unit, you can purchase a fully assembled and tested amplifier here:
👉 https://www.tindie.com/products/rfcore/wideband-rf-power-amplifier-01-8000-mhz-05w/

---

## ☕ Support the Author

If you appreciate this project and want to support future releases:  
- Donate via [PayPal](https://www.paypal.com/paypalme/vlshok)  
- Crypto (USDT TRC20): `TJiioa8RwEwcmAGNm4CvzLA9rCVcxkxZGR`

---

## 📄 License

This project is provided for **non-commercial laboratory and educational use only**.  
Redistribution, resale, or integration into commercial products is not permitted without written permission.

---

## 📬 Contact

- ✉️ Email: shokirov8751@gmail.com  
- 🔗 LinkedIn: [linkedin.com/in/ee7975](https://www.linkedin.com/in/ee7975/)

© 2025 Vladislav Shokirov
