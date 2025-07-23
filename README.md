# ESPhome-Sinilink-WFPOW
# ESP Modbus Uart Controller
* https://templates.blakadder.com/sinilink_XY-WFPOW.html

* GPIO 1 = TX  (UART, Sensor, Output)
* GPIO 3 = RX  (UART, Sensor, Output)
* GPIO 2 = inverted LED
* GPIO 4 = mechanical Button

![entity](picture/sinilink_XY-WFPOW_pinout.jpg "entity")
![entity](picture/cable.png "entity")

| Pin   | Name      | Function - Shelly Dimmer 1    |
| ----- | --------- | ----------------------------- |
| GPIO1     | TX       | UART TX                     
| GPIO2     | LED    | inverted LED                  
| GPIO3     | OCS_OUT   | -                          
| GPIO4     | NRST      | NRST                       
| 5V     | VDDA      | 5V Power Input                           |
| GND     | GND       | Board Ground                   |
