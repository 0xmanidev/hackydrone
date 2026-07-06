<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/af8d40bb-b481-4f43-abf3-46c2357688b5" />

# HACKYDRONE
This is my project for Outpost. It's an F450-style drone with a custom-designed frame, a custom flight controller, and a strong focus on keeping costs low without sacrificing performance. The drone runs Betaflight firmware and uses a SpeedyBee ESC for reliable motor control.

This project is built with the help of Hackclub and the program submitted to
[Outpost](https://outpost.hackclub.com/) / [Stardance](https://stardance.hackclub.com/)

<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/fa62bf5d-a2da-4260-8835-5a28af12c650" />


# Building

Clone the repository:

```bash
git clone https://github.com/0xmanidev/hackydrone.git

cd hackydrone
```

Compile firmware:

```bash
cd firmware/betaflight-2025.12.5

make TARGET=<BOARD_NAME>
```

---
## PCB

The `pcb/` directory contains everything required to manufacture the custom flight controller.

Included files:

- Complete KiCad project
- Bill of Materials (BOM)
- IPC netlist
- Manufacturing outputs

These files can be directly submitted to PCB fabrication services.

<img width="1402" height="1122" alt="image" src="https://github.com/user-attachments/assets/e5cae8ec-96a2-4c79-97fd-0c498df52f41" />
for more accurate and interactive schematics view the pcb/flight-controller -flight-controller.kicad_Sch,sensor.kicad_sch


---
# 3d model
<img width="1672" height="941" alt="3d-mockup" src="https://github.com/user-attachments/assets/5aec690e-e9e3-41bc-be3e-08eb35fff007" />

# Flight controller
<img width="1723" height="952" alt="pcb" src="https://github.com/user-attachments/assets/995c2f2f-041c-4c82-9691-bbb73a5d9286" />

# Components(these are the only after market components)
<div align="center">
<img width="250" alt="image" src="https://github.com/user-attachments/assets/b2f98be9-c86e-4d2e-89f0-5abe03dd35bb" />
<img width="250" alt="image" src="https://github.com/user-attachments/assets/2ef3648b-71e3-443e-8dda-f38a213b8c39" />
<img width="250" alt="image" src="https://github.com/user-attachments/assets/372d0393-9c08-4067-b487-69920c4ee167" />
</div>
<div align="center">

</div>

---

# Current Status

| Component | Status |
|-----------|--------|
| Frame Design | ✅ Complete |
| Flight Controller PCB | ✅ Complete |
| Firmware | ✅ Working |
| CAD Models | ✅ Complete |
| PCB Manufacturing Files | ✅ Included |
| Flight Testing | 🚧 In Progress |

---
# References

## STM32F405RGTx Microcontroller
- Datasheet:
  https://www.st.com/resource/en/datasheet/stm32f405rg.pdf
- Reference Manual (RM0090):
  https://www.st.com/resource/en/reference_manual/dm00031020.pdf
- Programming Manual:
  https://www.st.com/resource/en/programming_manual/dm00046982.pdf

---

## MPU-6050 6-Axis IMU
- Product Specification:
  https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Datasheet1.pdf
- Register Map:
  https://invensense.tdk.com/wp-content/uploads/2015/02/MPU-6000-Register-Map1.pdf

---

## ICM-20948 9-Axis IMU
- Datasheet:
  https://invensense.tdk.com/wp-content/uploads/2024/03/DS-000189-ICM-20948-v1.6.pdf
- Register Map:
  https://invensense.tdk.com/wp-content/uploads/2024/03/RM-000189-ICM-20948-v1.3.pdf

---

## BMP280 Barometric Pressure Sensor
- Datasheet:
  https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf

---

## AP63303WU 3A Buck Converter
- Datasheet:
  https://www.diodes.com/assets/Datasheets/AP63303_AP63357.pdf

---

## USBLC6-2SC6 USB ESD Protection
- Datasheet:
  https://www.st.com/resource/en/datasheet/usblc6-2.pdf

---

## LD39015M18R 1.8V Low Dropout Regulator
- Datasheet:
  https://www.st.com/resource/en/datasheet/ld39015.pdf

---

## NTS0104PW 4-bit Voltage Level Translator
- Datasheet:
  https://assets.nexperia.com/documents/data-sheet/NTS0104.pdf

---

## AO3401A P-Channel MOSFET
- Datasheet:
  https://aosmd.com/res/data_sheets/AO3401A.pdf

---

## TS-1187A Push Button Switch
- Datasheet:
  https://www.ckswitches.com/media/1457/ts.pdf

---

## 16 MHz Crystal Oscillator
- Example Reference (Abracon):
  https://abracon.com/Resonators/ABM3.pdf

---

## Micro USB Connector
- USB 2.0 Specification:
  https://www.usb.org/document-library/usb-20-specification

---

# Design References

- STMicroelectronics AN4488 – Getting Started with STM32F4 Hardware Development
  https://www.st.com/resource/en/application_note/dm00077036.pdf

- AN2867 – Oscillator Design Guide for STM32 Microcontrollers
  https://www.st.com/resource/en/application_note/cd00221665.pdf

- UM10204 – I²C-bus Specification and User Manual
  https://www.nxp.com/docs/en/user-guide/UM10204.pdf

- USB 2.0 Specification
  https://www.usb.org/document-library/usb-20-specification
AI USAGE : RESEARCH purposes and for mockups and visuals 

# credits : hackclub community - stasis community for helping out in making and outpost team for staying active and resolving queries
MADE with love by 0xmanidev
