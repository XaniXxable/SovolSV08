# Klipper Backup & Configuration for the Sovol SV08

This repository contains my **Klipper configuration and backup files**.  

Modifications:
- **MAINLINE KLIPPER**
- **PROBE** BTT Eddy
- **NOZZLE UPGRADE** 0.8 Hardened Steel

The purpose of this repo is to keep my printer settings version-controlled, easy to restore, and publicly accessible for reference or troubleshooting.  

---

## Repository Structure  

```text
├── printer.cfg           # Main Klipper configuration
├── Macro.cfg             # G-code macros
└── README.md             # This file
```

## Troubleshooting Reference
These are some common issues I encountered and fixes I used:
 * BTT Eddy - Tap failed: 15 errors, last: Error during homing probe: Sensor error (Over-range Error Amplitude Error) at toolhead z=XXXX: Have a look at this [post](https://github.com/vvuk/eddy-ng/issues/40)
