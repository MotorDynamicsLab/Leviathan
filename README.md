![Leviathan_Mainboard](/Media/product_img_web2.jpg "Leviathan Mainboard")

# Voron Leviathan
The Voron Leviathan V1.2 is collaboration between JNP and the team at LDO to create a controller board specific for the needs of Voron 3D printers. It features: 
- STM32F446 Microcontroller at 180Mhz clock speed. 
- Reverse polarity protection for main power supply and HV Stepper supply input
- Superior stepper driver cooling (passive)
- Dedicated mounting space for a Raspberry Pi 3,4,5 or Zero 2W
- Dedicated power supply and uart port for Raspberry Pi
- 5x Integrated TMC2209 stepper drivers. 
- 2x Integrated 48V rated TMC5160 stepper drivers. 
- 4x Fan ports with flyback protection, 5V/24V selectable voltage, and tachometer inputs. 
- 4x Thermistor ports with 2k2 ohm pullup resistors. 
- 1x Dedicated LED strip with flicker free dimming down to 1%.
- 1x Neopixel port.
- 1x Hotend power output up to 180W. 
- 1x Hotbed power output up to 240W
- 1x Dedicated Z probe port with selectable voltage and integrated diode.
- 3x Endstop ports and a filament sensor port 

## Setup Guide
https://ldomotion.com/p/guide/VORON-Leviathan-V12

## Electrical Specifications
| Parameter                 | Symbol             |  Min  | Typ   | Max   | Unit | Comments |
| --------------            | ------------------ | ----- | ----- | ----- |----- | -------- |
| Main Supply Voltage       | V<sub>in</sub>     | 18    | 24    | 28    |  V   | Supply voltage for the entire PCB except for HV stepper drivers |
| HV Stepper Supply Voltage | V<sub>HV</sub>     | 24    | 48    | 55    |  V   | Supply voltage for the HV stepper drivers |
| RPi Supply Out            | I<sub>RPI</sub>    |       |       | 3     |  A   | Current rating of Raspberry Power supply output |
| Hotend Current            | I<sub>he</sub>     |       |       | 7.5   |  A   | Current rating of hotend channel |
| Heatbed Current           | I<sub>hb</sub>     |       |       | 10    |  A   | Current rating of heatbed channel |
| Fan Current               | I<sub>fan</sub>    |       |       | 0.5   |  A   | Current rating per fan channel |
| Stepper Current           | I<sub>mot</sub>    |       |       | 2     |  A   | Current rating of each TMC2209 stepper channel |
| HV Stepper Current        | I<sub>hv_mot</sub> |       |       | 3     |  A   | Current rating of each TMC5160 stepper driver |
| Neopixel Current          | I<sub>rgb</sub>    |       |       | 0.5   |  A   | Current rating Neopixel port |
| LED-Strip Current         | I<sub>led</sub>    |       | 0.35  |       |  A   | Current rating of LED strip |
| Endstop IO Level          | V<sub>stop</sub>   |       | 3.3   | 5.0   |  V   | Logic level of endstop input |
| Filament Sensor IO Level  | V<sub>fil</sub>    |       | 3.3   | 5.0   |  V   | Logic level of filament sensor input |