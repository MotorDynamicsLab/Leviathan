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
| Parameter          |  Minimum | Typical | Maximum | Unit | Comments |
| --------------     | -------- | ------- | ------- |----- | -------- |
| Main Power Input   |          |   24    |         |  V   | Supply voltage for the entire PCB except for HV stepper drivers |
| HV Power Input     |          |   48    |         |  V   | Supply voltage for the HV stepper drivers |
| RPi Power Out      |          |         |         |  A   | Current rating of Raspberry Power supply output |
| Heater Current     |          |         |         |  A   | Current rating of each hotend/heater mosfet |
| Fan Current        |          |         |         |  A   | Current rating of each fan mosfet |
| Stepper Current    |          |         |         |  A   | Current rating of each TMC2209 stepper driver |
| HV Stepper Current |          |         |         |  A   | Current rating of each TMC5160 stepper driver |