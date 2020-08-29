# Multi-tracker

##Tracking device dev board with Sigfox, Wifi and GPS functionality

This board is designed to allow testing and development of a tracking device using Sigfox, WiFi and GPS location tracking. It also breaks out all useful pins and indicators on both the WSS10R1AT Sigfox module, and the SIM28ML GPS module.

A P-channel mosfet supplies power to the GPS module, so that it can be enabled and disabled as needed to save power. The LEDs can also be enabled and disabled via a jumper, so that realistic power consumption tests can be performed if needed.

Gerbers are included, ready to be submitted to JLCPCB or PCBWay (not tested with other services)

3D model render with CAD download can be found [here](https://a360.co/2Z3gr4b)

![Render](./images/tracker-brd-v1.jpg?raw=true)
