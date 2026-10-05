# Custom ESP32 Development Board

A custom development board based on the ESP32, designed to provide a practical hardware platform for embedded-system development, peripheral interfacing, and PCB design practice.

## Project Overview

This project involves the schematic design and PCB layout of a custom ESP32 development board using **KiCad**.

The objective is to move beyond development boards such as the ESP32 DevKit and design a custom board with the essential circuitry required for ESP32-based embedded applications.

## Features

* ESP32-based custom development board
* Custom schematic design
* Custom PCB layout
* 3.3 V power architecture
* ESP32 power decoupling
* GPIO access for external peripherals
* Programming/debug interface
* Designed using KiCad
* PCB design with practical routing and component placement considerations

## Hardware Design

### Main Controller

* **ESP32**
* 32-bit dual-core microcontroller
* Wi-Fi and Bluetooth connectivity
* Multiple GPIO interfaces
* ADC and other peripheral interfaces

### Power Supply

The board includes the required power circuitry for the ESP32 and its peripherals.

Decoupling capacitors are placed close to the power pins to help reduce supply noise and provide transient current during ESP32 operation.

### PCB Design

The PCB was designed with attention to:

* Component placement
* Signal routing
* Power routing
* Ground connectivity
* Decoupling capacitor placement
* Trace-width selection
* Design Rule Check (DRC)

## Design Tool

**KiCad**

The project includes:

```text
├── Schematic
│   └── Custom ESP32 Development Board schematic
│
└── PCB
    └── Custom ESP32 Development Board PCB layout
```

## Repository Contents

| File                  | Description      |
| --------------------- | ---------------- |
| `esp32 (1).kicad_sch` | KiCad schematic  |
| `esp32 (1).kicad_pcb` | KiCad PCB layout |

## Learning Objectives

This project was developed to strengthen practical skills in:

* Embedded hardware design
* ESP32 hardware interfacing
* Circuit schematic design
* PCB layout
* Component placement
* PCB routing
* Power and decoupling design
* KiCad
* Hardware debugging and design validation

## Project Status

**Hardware design:** In progress / under development

The schematic and PCB design have been created in KiCad. Further hardware validation and testing will be performed after PCB fabrication and assembly.

## Future Improvements

* PCB fabrication and assembly
* Hardware bring-up and testing
* Verify all power rails
* Test ESP32 programming and debugging
* Test GPIO and peripheral interfaces
* Add project photographs and PCB 3D views
* Document hardware validation results

## Author

**Priya Udhayakumar**

Electronics & Communication Engineer
Focused on Embedded Systems and PCB Design
