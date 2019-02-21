# esp32-bigclown-climate
Use the bigclown climate module with your ESP32!

BigClown creates awesome open source hardware for makers!
This repository shows how to use their Climate Module with an ESP32.
You can get the module here: https://shop.bigclown.com/climate-module/

The module has four I2C sensors:

* TMP112AID (address 0x48)
* SHT20 (address 0x40)
* MPL3115A2 (address 0x60)
* OPT3001 (address 0x44)

# Software Installation

Use platformio for this project.

# Hardware Installation

Use your favourite ESP32 dev board and connect it like this:


PIN | ESP32 Pin | Climate Module Pin
--- | --- | ---
GND | GND | 15
VCC | 3V3 | 16
SCL | 22 | 17
SDA | 21 | 18
