# Sinilink-WFPOW
#  Modbus Uart Controller

```yaml
esp8266:
  board: esp8285

# if use GPIO1 and GPIO3 ( TX and RX ) logger off (baudrate: 0)
logger:
  baud_rate: 0
```


| Pin   | Name      | Function
| ----- | --------- | ----------------------------- 
| GPIO1     | TXD       | UART TX                 
| GPIO2     | LED       | inverted LED                  
| GPIO3     | RXD       | UART RX                          
| GPIO4     | Button    | meachnical Button                      
| 5V        | VDD       | 5V Power Input regulator to 3.3V                          
| GND       | GND       | Board Ground
| 3.3V      | VDDA      | 3.3V alternative                      
| IO0       | flash     | to GND to flash
| RST       | Reset     | Restart esp

![entity](picture/sinilink_XY-WFPOW_pinout.jpg "entity")
![entity](picture/cable.png "entity")

# Useful links
*  [Tasmota Sinilink XY-WFPOW](https://templates.blakadder.com/sinilink_XY-WFPOW.html)
  
