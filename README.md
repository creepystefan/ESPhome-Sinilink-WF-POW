# ESPhome-Sinilink-WFPOW
# ESP Modbus Uart Controller
* https://templates.blakadder.com/sinilink_XY-WFPOW.html

* GPIO 1 = TX  (UART, Sensor, Output)
* GPIO 3 = RX  (UART, Sensor, Output)
* GPIO 2 = inverted LED
* GPIO 4 = mechanical Button

![entity](picture/sinilink_XY-WFPOW_pinout.jpg "entity")
![entity](picture/cable.png "entity")

| Pin   | Name      | Function - Shelly Dimmer 1    | Function - Shelly Dimmer 2    | Pin type |
| ----- | --------- | ----------------------------- | ----------------------------- | - |
| GPIO     | VDD       | 3V3                           | 3V3                           |  |
| 2     | OCS_IN    | -                             | -                             |  |
| 3     | OCS_OUT   | -                             | -                             |  |
| 4     | NRST      | NRST                          | NRST                          |  |
| 5     | VDDA      | 3V3                           | 3V3                           |  |
| 6     | PA0       | CF1 HLW8012                   | -                             | Input  |
