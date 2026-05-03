# Xiao-ESP32C3-4-Channel-Servo-Shield
A compact 4-channel servo expansion board for XIAO ESP32C3 / XIAO series MCUs. Features independent servo ports, a power switch, and a bulk capacitor for stable power delivery, making it perfect for small robotics and servo-based projects.
# Xiao ESP32-C3 4-Channel Servo Shield

![EasyEDA](https://img.shields.io/badge/Designed_in-EasyEDA-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the complete hardware design files for a **4-Channel Servo Shield** compatible with the XIAO ESP32C3 and other XIAO-series development boards!

![3D Render](images/3d_render.png) <!-- Make sure to place your 3D render image in an 'images/' folder -->

## ✨ Project Overview
-----------------------------------------------
<img width="700" height="501" alt="Schematic_Xiao_ESP32C3_servo_2026-05-02" src="https://github.com/user-attachments/assets/37f6008b-3496-4c5f-bd7a-5cbe44153d68" />

-----------------------------------------------
<img width="622" height="597" alt="Xiao_ESP32C3_servo_3D_Top_View" src="https://github.com/user-attachments/assets/059ba018-0271-4b02-a961-71d55a3cc6b5" />

-----------------------------------------------
<img width="656" height="603" alt="Xiao_ESP32C3_servo_3D_Bottom_View" src="https://github.com/user-attachments/assets/598ad5a7-1039-4ada-8064-55ac559134bb" />

-----------------------------------------------
<img width="486" height="471" alt="Xiao_ESP32C3_servo_2D_View" src="https://github.com/user-attachments/assets/9067e129-ddfc-4fd6-99dc-e23a365e1e9f" />

-----------------------------------------------
This shield is a minimalistic yet functional expansion board that allows you to easily connect and control up to 4 micro servos using a XIAO MCU. It is designed to fit directly onto the standard XIAO footprint.

*   **Core Purpose:** Control up to 4 micro servos (SG90, MG90, etc.) using the XIAO ESP32-C3.
*   **Powering:** Uses the XIAO's 5V output pin for servo power.  *(Note: For heavy loads, consider direct external power routing via `B+` pads or a voltage regulator module).*
*   **Design Style:** Very compact, matching the small form factor of the XIAO module.

## 📂 Repository Structure
```text
/
├── images/                               # PCB renders and screenshots
├── Schematic_Xiao_ESP32C3_servo_2026-05-02.pdf  # Full circuit schematics
├── PCB_PCB_Xiao_ESP32C3_servo_2026-05-02.pdf    # PCB layout visual
├── BOM_Xiao_ESP32C3_servo_2026-05-02.csv        # Bill of Materials
└── PickAndPlace_PCB_Xiao_ESP32C3_servo_2026-05-02.csv # Pick & Place coordinates
