# 🧾 A002 RF Power Amplifier – PCB Production Files

This folder contains all necessary files to manufacture the printed circuit board (PCB) for the **A002 Wideband RF Power Amplifier (0.1–8000 MHz, 0.5W)**.  
Designed for professional lab use and prototyping environments.

---

## 📁 Folder Contents

| File                             | Description                                |
|----------------------------------|--------------------------------------------|
| `Gerbers.zip`                    | Complete set of Gerber and drill files     |
| `Pick Place for PCB1.csv`        | Standard XY placement file for SMT assembly |
| `Bill of Materials`              | Full component list with designators       |
| `Drawing.pdf`                    | Dimensional drawing with board outline     |
| `Screenshot_*.png`               | Visual reference for layout or simulation  |
| `README.md`                      | This file – PCB fabrication guide          |

---

## 📦 PCB Ordering Specifications

| Parameter                    | Value                         |
|-----------------------------|-------------------------------|
| Layers                      | 4                             |
| Board Thickness             | 1.2 mm                        |
| Material                    | FR-4 TG155                    |
| Outer Copper                | 1 oz (35 µm)                  |
| Inner Copper                | 0.5 oz (15 µm)                |
| Surface Finish              | HASL (with lead)              |
| Solder Mask Color           | Green                         |
| Silkscreen Color            | White                         |
| Via Type                    | Plated through-hole only      |
| Via Plugging                | Plugged                       |
| Hole Tolerance              | ±0.2 mm                       |
| Minimum Drill Size          | 0.3 mm                        |
| Stackup Type                | JLC04121H-1080A (confirmed)   |

---

### 📚 Layer Stackup

| Layer            | Material Type | Thickness   |
|------------------|----------------|-------------|
| Top Layer        | Copper         | 0.035 mm    |
| Prepreg (1080)   | Dielectric     | 0.084 mm    |
| Prepreg (7628)   | Dielectric     | 0.210 mm    |
| Inner Layer L2   | Copper         | 0.0152 mm   |
| Core             | FR4 Core       | 0.5 mm      |
| Inner Layer L3   | Copper         | 0.0152 mm   |
| Prepreg (7628)   | Dielectric     | 0.210 mm    |
| Prepreg (1080)   | Dielectric     | 0.084 mm    |
| Bottom Layer     | Copper         | 0.035 mm    |

---

### 🗂️ Gerber File Mapping

| File Name   | Layer Description             |
|-------------|-------------------------------|
| `GTL`       | Top Copper                    |
| `GBL`       | Bottom Copper                 |
| `G1`, `G2`  | Inner Layers 1 & 2            |
| `GTS`, `GBS`| Top and Bottom Solder Mask    |
| `GTP`, `GBP`| Top and Bottom Silkscreen     |
| `GM1`       | Mechanical Layer / Outline    |
| `TXT`       | Drill file (PTH only)         |

---

## 📝 Notes

- Only **plated through-hole** vias are used in this design.
- No blind/buried vias or impedance control required.
- Files are optimized for use with **JLCPCB**, but compatible with most manufacturers.

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

