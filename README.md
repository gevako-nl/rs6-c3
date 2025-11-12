# Gevako RS6-C3 | 6-channel Smart Switch for Home Assistant

## Introduction
The Gevako RS6 is a 6-channel Smart Switch suitable for Home Assistant by using ESPHome. Six individual relays with a maximum switching current of 16 A at max 250 VAC / 30 VDC. Using the powerful ESP32-C3 processor.

[<img width="200" height="200" alt="RS6-2" src="https://github.com/user-attachments/assets/4f97974d-c294-44d3-8330-2c8b5f93b171" />](https://gevako.nl/shop/gevako-rs6/)

### [Gevako RS6](https://gevako.nl/shop/gevako-rs6/)

## Pinout
#### ESP32-C3 GPIO pinout
| GPIO pin | Description             |
| :---     | :---                    |
| GPIO00   | Output 1                |
| GPIO01   | Output 2                |
| GPIO03   | Output 3                |
| GPIO04   | Output 4                |
| GPIO05   | Output 5                |
| GPIO06   | Output 6                |
| GPIO07   | Green LED / BOOT        |
| GPIO10   | Power source detection  |

## Electrical schematic
| Number | Label | Description                                       |
| :---   | :---  | :---                                              |
| 1      | L1    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 2      | O1    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 3      | L2    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 4      | O2    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 5      | L3    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 6      | O3    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 7      | L4    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 8      | O4    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 9      | L5    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 10     | O5    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 11     | L6    | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 12     | O6    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 13     | L     | Phase 230 VAC.                                    |
| 14     | N     | Null 230 VAC.                                     |
| 22     | B     | BOOT.                                             |
| 23-24  | USB   | USB-C connector. Max 5 VDC with a current of 1 A. |

<img width="600" height="620" alt="RS6" src="https://github.com/user-attachments/assets/3187ef04-c485-4fcf-9b61-99d80f0bda09" />

## Electial wiring example
<img width="600" height="739" alt="RS6 example_2 0 1" src="https://github.com/user-attachments/assets/3e578544-4c16-45c5-b363-5d55fe7742ed" />
