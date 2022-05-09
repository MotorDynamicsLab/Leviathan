# Voron Leviathan
The Voron Leviathan is collaboration between JNP and the team at LDO to create a controller board specific for the needs of Voron 3D printers. It features: 
- STM32F446 Microcontroller at 180Mhz clock speed.
- Five integrated TMC2209 stepper drivers 
- Two integrated 48V rated TMC5160 stepper drivers 
- Four fan ports with flyback protection, selectable voltage, and tachometer inputs
- Four thermistor ports with 2k2 ohm pullup resistors
- Dedicated LED strip and neopixel ports.
- Dedicated Z probe port with selectable voltage and integrated diode.
- Three endstop ports and a filament sensor port 
- Dedicated mounting space for a Raspberry Pi 3,4, or Zero 2W
- Dedicated power supply and uart port for Raspberry Pi

## Electrical Specifications
| Parameter                 | Symbol             |  Min  | Typ   | Max   | Unit | Comments |
| --------------            | ------------------ | ----- | ----- | ----- |----- | -------- |
| Main Supply Voltage       | V<sub>in</sub>     | 18    | 24    | 28    |  V   | Supply voltage for the entire PCB except for HV stepper drivers |
| HV Stepper Supply Voltage | V<sub>HV</sub>     | 24    | 48    | 55    |  V   | Supply voltage for the HV stepper drivers |
| RPi Supply Out            | I<sub>RPI</sub>    |       |       | 3     |  A   | Current rating of Raspberry Power supply output |
| Hotend Current            | I<sub>he</sub>     |       |       | 6     |  A   | Current rating of hotend channel |
| Heatbed Current           | I<sub>hb</sub>     |       |       | 12.5  |  A   | Current rating of heatbed channel |
| Fan Current               | I<sub>fan</sub>    |       |       | 0.5   |  A   | Current rating per fan channel |
| Stepper Current           | I<sub>mot</sub>    |       |       | 2     |  A   | Current rating of each TMC2209 stepper channel |
| HV Stepper Current        | I<sub>hv_mot</sub> |       |       | 4     |  A   | Current rating of each TMC5160 stepper driver |
| Neopixel Current          | I<sub>rgb</sub>    |       |       | 0.5   |  A   | Current rating Neopixel port |
| LED-Strip Current         | I<sub>led</sub>    |       | 0.3   |       |  A   | Current rating of LED strip |
| Endstop IO Level          | V<sub>stop</sub>   |       |       | 3.3   |  V   | Logic level of endstop input |
| Filament Sensor IO Level  | V<sub>fil</sub>    |       |       | 3.3   |  V   | Logic level of filament sensor input |
| SWD IO Level              | V<sub>SWD</sub>    |       |       | 3.3   |  V   | Logic level of SWD port input |
| Thermistor Level          | V<sub>th</sub>     |       |       | 3.3   |  V   | ADC level of thermistor input |