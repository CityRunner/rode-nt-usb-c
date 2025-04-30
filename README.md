# RODE NT-USB-C

## USB-C Adapter for RØDE NT-USB Microphone

Drop-in USB-C daughterboard for the RØDE NT-USB microphone, replacing the original USB-B port.
Designed to fit inside the existing housing—no modification required.
Includes a power LED visible through a transparent 3D-printed insert.
All components are 1206 SMD for easy hand soldering and compact layout.

## Features

- **USB-C Connector**: 16-pin edge-mount receptacle.
- **Power Indicator**: Red LED with 220 Ω current-limiting resistor.
- **CC Biasing**: Two 5.11 kΩ pull-down resistors for host detection.

## Images

![screenshot](https://raw.githubusercontent.com/CityRunner/rode-nt-usb-c/refs/heads/main/misc/pcb.png?raw=true)

## Component List:

| Reference | Qty | Value                            | Digikey Number               |
|-----------|-----|----------------------------------|------------------------------|
| D1        | 1   | LED RED CLEAR 1206 SMD           | 754-APTR3216SECK/J3-PRVCT-ND |
| J1        | 1   | CONN RCP USB2.0 TYP C 24P SMD RA | 2073-USB4105-GF-ACT-ND       |
| J2        | 1   | CONN BRD STACK 2.00 40POS        | 612-TW-40-11-S-S-170-100-ND  |
| R1        | 1   | RES 220 OHM 1% 1/4W 1206         | 311-220FRCT-ND               |
| R2, R3    | 2   | RES 5.11K OHM 1% 1/4W 1206       | RMCF1206FT5K11CT-ND          |

> ℹ️ **Important:** The J2 connector must be **exactly** this size (mm):

- **Pitch:** 2.00
- **Length:**
  - **Overall:** 10.08
  - **Post:** 3.22
  - **Stack:** 4.31
  - **Tail:** 2.54
