# KEA_ESP
KEA's group effort on working with the ESP8266 wifi module.

Requires the ESP8266 board library for the Arduino IDE.

File - preferences - sketchbook location: "http://arduino.esp8266.com/stable/package_esp8266com_index.json"
Install:
Tools - Board - Board Manager --- esp8266

Following this tutorial with a few modifications (https://www.hackster.io/ROBINTHOMAS/esp8266-esp-01-webserver-7248ca)

Connected 3v3 FTDI (USB powered) straight to ESP board, grounded GPIO0, TX/RX connected, CH_PD tied to VCC.
GPIO0 stays grounded even after flashing software.

Also tested and confirmed powered directly regulated from Arduino (no external power) and flashed over serial connection.

NOTE: -v e r y- unpredictable operation. Simply repeating the flashing process again and again eventually works successfully,
but it's unclear what the issue is that makes it so fragile.

.INO file included here is written by Robin Thomas.


