# ESP-Eyes

Halloween eyes with handheld bluetooth controller using an esp32. 

This was a big, big, help https://github.com/BigJBehr/ESP32-Bluetooth-BLE-Remote-Control

Combined the above bluetooth controller example with some example effects and some homemade eyeballs.

Hardware required:

VR BOX Bluetooth Remote Controller or equivalent.
2 TFT Displays, I used the 1.3 inch 
Esp32 Dev Kit
Wires and soldering equipment


Libraries required:

#include "BLEDevice.h"     Bluetooth
#include <FS.h>            Spiffs
#include "SPIFFS.h" 
#include <TFT_eSPI.h>      Display

# To use:

See the instructions here for bluetooth details.
https://github.com/BigJBehr/ESP32-Bluetooth-BLE-Remote-Control

After connecting to Bluetooth, I press two buttons to begin, then another to wake it from the black starry
sleep and move the eyeballs around, carefully trying not anger it.

Have fun.


