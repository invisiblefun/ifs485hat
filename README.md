# ifs485hat
The bootstrap code for setting up environment for our dedicated hardware rpi 485 hat. 


## Introduction : 
The IFS RPI 485 HAT will enable your Raspberry Pi to communicate with other devices stably in long-distance via RS485 functions. Also, you can access real time by IFS RPI 485 HAT. The real time clock maintains year, month, date, hours, minutes, seconds.


## Product Description: 
The IFS RPI 485 HAT is a UART to RS485 serial converter for the Raspberry Pi. The RS485 Port is connected to the UART port on the Raspberry Pi using a MAX13487 interface. The MAX13487 IC converts the 5V UART port to RS485 and allow communication with compatible devices. 

Our IFS RPI 485 HAT contains protection using TVS Diodes in SMBJ series, which is designed specifically to protect sensitive electronic equipment from voltage transients by lightning and other transient voltage events.

For the real time clock, it is done by an extremely accurate IC, DS3231MZ. The device incorporates a battery input to maintain accurate timekeeping when the main power to the device is interrupted. 


## Specifications:
Dimension : 64.87mm x 56.33mm
Mounting hole size: 3.0mm


## Remark: 
The IFS RPI 485 HAT can also be used without Raspberry Pi. There are pinouts named RX, TX, 5V and GND, which allow you to use it for RS485 communication only.
The battery of real time clock involves CR2032 in 3V to run.



```
sudo raspi config
```
