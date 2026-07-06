<img width="2172" height="724" alt="image" src="https://github.com/user-attachments/assets/af8d40bb-b481-4f43-abf3-46c2357688b5" />

# HACKYDRONE
This is my project for Outpost. It's an F450-style drone with a custom-designed frame, a custom flight controller, and a strong focus on keeping costs low without sacrificing performance. The drone runs Betaflight firmware and uses a SpeedyBee ESC for reliable motor control.

This project is built with the help of Hackclub and the program submitted to
[Outpost](https://outpost.hackclub.com/) / [Stardance](https://stardance.hackclub.com/)

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
