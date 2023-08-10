# WRIP-VAPE
WRIST MOUNTED VAPE

# WRIP Electronics Project

This repository contains the design files for the WRIP electronics project, a wrist-mounted battery-powered vape developed by kodar embedded technologies limited.

## Overview

- **Design**: Wrist-mounted battery-powered vape with a refillable pod design.
- **Activation**: Breath triggered vape action.
- **Battery**: Ultrathin 250-milliampere lithium battery measuring 2.5cm by 1cm.
- **Coil**: 2-ohm nichrome wire coil designed for rapid heating.
- **Charging**: Side-mounted type-c port for rapid charging.
- **Straps**: Apple Watch style slide-in exchangeable wrist straps.
- **Indicators**: 4-stage battery level indicator.

## Hardware Specifications

- **Microcontroller**: An 8-bit microcontroller with a power level selector to fit vaping preferences.
- **LEDs**: 0-25, 25-50, 50-75, 75-100% LEDs for power level selection and battery level indication.
- **Safety**: Lithium-ion battery equipped with protection circuitry to prevent overcharge, over-discharge, short circuits, and overheating.

## Software Features

- **Display**: Shows battery level and vape power level.
- **Sleep Mode**: The device is mostly in sleep mode but wakes up at the push of a button. It stays on for 5 minutes before automatically switching off if not used.
- **Power Regulation**: Regulates power based on 58kHz PWM generated signals.

## Power Details

- **Charging**: Charges from 0-100% in 40 minutes.
- **Weight**: Weighs just 8g.
- **Discharge Rate**: Features a 15c discharge rate.
- **Dimensions**: 14mm wide, 38mm long, and 5mm thick.

## Repository Structure

- `WRIP-backups`: Directory containing backup files for the project.
- `WRIP.kicad_prl`: KiCad project related file.
- `WRIP.step`: 3D model of the project in STEP format.
- `WRIP.kicad_pro`: KiCad project file.
- `#auto_saved_files#`: Directory containing auto-saved files.
- `kicad libraries`: Directory containing KiCad libraries used in the project.
- `WRIP.kicad_sch`: KiCad schematic file.
- `WRIP.kicad_pcb`: KiCad printed circuit board (PCB) design file.
- `fp-info-cache`: Directory related to footprint information cache.

## Getting Started

1. Clone this repository.
2. Open the `WRIP.kicad_pro` file using KiCad to view the project.

## Contributing

Please read the contribution guidelines before making any changes.

## License

This project is licensed under the MIT License.

