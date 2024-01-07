# AlarmSystem32
Anti-theft central unit based on esp32 with ESPHome Firmware

## PCB

Fully Assembled PCB



<img src="https://github.com/cristiandc01/AlarmSystem32/blob/main/Images/full_board.jpeg" width="600"/>

Revision 1.5

<img src="https://github.com/cristiandc01/AlarmSystem32/blob/main/Images/AlarmSystem32_PCB_FRONT_V15.png" width="200"/>  <img src="https://github.com/cristiandc01/AlarmSystem32/blob/main/Images/AlarmSystem32_PCB_REAR_V15.png" width="200"/>

## Features

 
 - 12V Power Supply input with support for ups power supply
 - 6 x 12V Inputs optocoupler
 - 2 x Dry-Contact Relay output
 - 1 x User Interface IO (for keypad, rfid reader, status led)
 - RF433 Receiver Support
 - I2C Bus
 - Support all I2C periferals like PN532 RFID Reader
 - ESP32 Based with bluetooth and wifi connection
 - ESPHome and HomeAssistant Support
 - P82B715 I2C BUS Extender integrated

## How to Build

It is possible to print the pcb through common printing services such as jlcpb.

Components can be purchased from lcsc along with pcbs by uploading the BOM file.

## REVISION 1.5

I Released a new version of the pcb: version 1.5

This version mainly adds the P82B715 I2C Bus Extender chip which allows the use of the i2c bus outside the system useful for connecting any card readers or zone extenders outside the main box
It also modifies the terminal block relating to the interfaces by opting for a screw terminal and adds a new pin on this interface. 



## Accessories

Many accessories can be added and configured to the system such as NFC readers, neopixel LEDs, fingerprint readers, displays, numeric keypads and IO expansion cards using the USER INTERFACE Pins.

Some Accessories created specifically for AlarmSystem:

- NFC Access Controller 
- I2C Input expansion board (https://github.com/cristiandc01/AlarmSystem32_INPUT)
- I2C Output expansion board
- Siren conversion board to I2C bus
- I2C Bus Extender Board (https://github.com/cristiandc01/AlarmSystem32_I2C_EX)
