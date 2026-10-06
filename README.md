# Hackpad

A 3-key macropad built around a Seeed XIAO RP2040. Each key is wired straight to its own pin, so the board needs no diodes.

![Hackpad](images/hackpad.png)

## Schematic
![Schematic](images/schematic.png)

## PCB
![PCB](images/pcb.png)
![PCB 3D view](images/pcb-3d.png)

## Case
A 3D printed base with a USB-C notch in the back wall, and a switch plate with three 14 mm holes.

![Case](images/case.png)

## Firmware
KMK firmware in `Firmware/main.py`. SW1, SW2 and SW3 are on pins D10, D9 and D8.

## BOM
| Item | Quantity |
|---|---|
| Seeed XIAO RP2040 | 1 |
| Cherry MX style switch | 3 |
| DSA keycap | 3 |
| M3 screw | 4 |
| M3 heatset insert | 4 |
| 3D printed case (base and plate) | 1 |

## Files
- `CAD/` assembled case model (STEP)
- `PCB/` KiCad schematic and PCB
- `Firmware/` KMK source
- `production/` gerbers, case parts and firmware
