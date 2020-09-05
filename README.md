# Multi-tracker

### Tracking device dev board with Sigfox, Wifi and GPS functionality

This board is designed to allow testing and development of a tracking device using Sigfox, WiFi and GPS location tracking. It also breaks out all useful pins and indicators on both the WSS10R1AT Sigfox module, and the SIM28ML GPS module.

A P-channel mosfet supplies power to the GPS module, so that it can be enabled and disabled as needed to save power. The LEDs can also be enabled and disabled via a jumper, so that realistic power consumption tests can be performed if needed.

The ESP8266 has GPIO16 connected to reset, to allow the use of deep sleep, with timer interrupt wake.

The i2C pins from the ESP8266 are broken out onto the header, to allow connection of sensors, displays etc as needed. Additionally the ADC input from the ESP8266 has also been broken out - the input uses a voltage divider, so it can read voltages from 0 to around 3.3v.

Please note that this board is designed to run from 3.3V or lower, as it has no on-board voltage regulation. This is deliberate, as the board is designed for testing and development. If there is interest I will make another version more suited to outdoor use, with regulator, charging circuit etc to run from lithium Ion batteries or a USB charger.

Gerbers are included, ready to be submitted to JLCPCB or PCBWay (not tested with other services)

3D model render with CAD download can be found [here](https://a360.co/2Z3gr4b)

![Render](./images/tracker-brd-v2.png?raw=true)
