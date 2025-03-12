# RODE NT-USB-C

## USB-C Adapter for RØDE NT-USB Microphone

This project involves designing and building a **drop-in USB-C daughterboard** to replace the original **USB-B** port in the **RØDE NT-USB**, enabling compatibility with modern USB-C connections.
The adapter includes a power LED indicator that shines through a transparent 3D-printed insert, and uses a compact, efficient design to fit within the microphone's housing.
All components are SMD 1206 for easy hand soldering.

## Features

- **USB-C Connector**: Uses a 16-pin USB-C connector for edge-mounting on the PCB.
- **Power LED**: Includes a red LED for power indication. **220Ω resistor** limits current to the LED, preventing burnout.
- **Shield Connection**: The **1MΩ resistor** connects the shield to the ground for proper grounding and noise reduction.
- **Biasing**: Two **5.11KΩ resistors** are used for voltage biasing or pull-up/down configurations.

## Component List:

| Reference | Qty | Value                            | Digikey Number               |
|-----------|-----|----------------------------------|------------------------------|
| D1        | 1   | LED RED CLEAR 1206 SMD           | 754-APTR3216SECK/J3-PRVCT-ND |
| J1        | 1   | CONN RCP USB2.0 TYP C 24P SMD RA | 2073-USB4105-GF-ACT-ND       |
| J2        | 1   | CONN HEADER VERT 5POS 2MM        | 2057-2PH1-05-UA-ND           |
| R1        | 1   | RES 1M OHM 1% 1/4W 1206          | 2019-HV732BTTD1004FCT-ND     |
| R2, R3    | 2   | RES 5.11K OHM 1% 1/4W 1206       | RMCF1206FT5K11CT-ND          |
| R4        | 1   | RES 220 OHM 1% 1/4W 1206         | 311-220FRCT-ND               |
