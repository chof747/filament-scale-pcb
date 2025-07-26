# Samla Filamentalist Electronics

## Idea

This is the electronics part of the filamentalist samla box which consists of:

### 1. The scale breakout for each Filamentalist station that contains:

- A header to read from a load cell
- An HX711 ADC controller and circutry to read the load cell
- A peripheral connector to connect to the led and the button on the outside of the box of the filamentalist station
- An IDC header to connect to the central mcu unit

### 2. An MCU Breakout

A board that bears the MCU and brain of the Filamentalist Box it has

- IDC receiving headers for each scale
- A header to connect to an SHT40X breakout for environmental control
- A 0.9" OLED
- A reset and a mod button to controll the oled

## Components

- Arduino Nano as the MCU
- 0.9" OLED
- 2x SMD Push Buttons
- 3 IDC headers
- 1 JST XH 2.54mm header (environmental sensor)

- HX711 ADC
- Screw terminal for Load cell connections
- IDC Header to MCU
- Peripheral JST xh 2.54mm for peripherals

## Revision History

**V1.0** - Send to production 26.07.2025