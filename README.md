# UHF Antenna Deployment Board

## Overview
The UHF Antenna Deployment Board receives RF signals from the UHF Transceiver Board and applies phase shifts of 0°, 90°, 180°, and 270° to feed a Left-Hand Circular Polarization (LHCP) antenna array.

## How It Works
1. **Input** — Receives RF signal from the UHF Transceiver Board
2. **Phase Shifting** — Splits and shifts the signal into 4 phases:
   - 0° 
   - 90°
   - 180°
   - 270°
3. **Output** — Feeds the phase-shifted signals to the LHCP antenna

## Files
| File | Description |
|---|---|
| `v1.SchDoc` | Schematic document |
| `PCB1.PcbDoc` | PCB layout document |
| `PCB1.PCBDwf` | PCB fabrication file |
| `UHF_Deployment.PrjPcb` | Altium project file |

## Tools Used
- Altium Designer

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
