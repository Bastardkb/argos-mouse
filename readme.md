# Argos mouse

An ergonomic mouse with a trackpad.

Engineered to be a full mouse replacement solution with high-quality, custom-developed components.

# Disclaimer

**This is a work in progress and not meant for ordering yet.**

# Required components

## 3d prints

The STL files are included in this Github repository, in the `files` folder.

| Description      | File                    | Notes                      |
| ---------------- | ----------------------- | ----------------------- |
| Case | `main.3mf` | |
| Switch holder | `switches.3mf` | |
| Trackpad holder | `trackpad holder.3mf` |  |
| Tent | `tent.3mf` | Optional |
| Trackpad holder | `trackpad holder.3mf` |  |

## Hardware

You can get a kit from Bastard keyboards directly. Alternatively, you can source components yourself.


| Part name      | Amount                    | Notes                      |
| ---------------- | ----------------------- | ----------------------- |
| Heated screw insert, M3x5x5 | 2 |  |
| M3 8mm torx screw | 3 | |
| M3 square nut | 1 | |
| Cirque trackpad | 1 | 40mm curved || 12-position FPC cable, 0.5mm pitch, same side contacts | 1      | Farnell, length TBD       |


Optional parts if you're using the tents

| Part name      | Amount                    | Notes                      |
| ---------------- | ----------------------- | ----------------------- |
| Heated screw insert, M3x5x5 | 3 |  |
| M3 8mm torx screw | 3 | |

## PCBs

You will need 2 PCBs for this mouse.

### Controller

- A RP2040-based board, the brain of the mouse
- The release section includes gerbers, BOM and POS files
- Order in 1.2mm thickness

### Switches

- Connects all the switches and add per-key RGB capabilities
- https://github.com/Bastardkb/argos-switches-pcb
- Order in 0.6mm thickness
- You can also instead handsolder or use amoebas, but then might have to modify the firmware.

## Print instructions

- Material: PLA
- Layer height: .15mm or .2mm
- Supports: everywhere*

*If using prusaslicer, using auto-painted supports will work as well.

# Build guide

You can find detailed instruction on the online documentation linked below.

# Links

- Discord: https://bastardkb.com/discord
- Website: https://bastardkb.com/
- Docs: https://docs.bastardkb.com

# License 

This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.
