# Teensy-Senix
Read ultrasonic distance measured by Senix ToughSonic sensors to Teensy/Arduino microcontrollers.

This code shows a method for reading the distance measured by continous ultrasonic sensors provided by Senix.

The sensor tested is a ToughSonic 3 (RS232 model) and should be connected through a MAX232-based conversion circuit to a 5V microcontroller serial port. The MAX232 chip is connected to a hardware serial port in a Teensy 3.5 mircrocontroller development system.

Output: ultrasonic distance measured in millimeters.

ToughSonic sensor is configured via SenixVIEW software to work in continous mode with 100 msec interval.

Connections: 
Yellow wire to pin 14 (T1OUT) in MAX232 IC - Gray wire to pin 13 (R1IN) in MAX232 IC - Brown wire to +24 VDC - Power supply - Blue wire to GND - pin 11 (T1IN)  in MAX232 IC ... pin 32 (TX4) in Teensy 3.5  - pin 12 (R1OUT) in MAX232 IC ... pin 31 (RX4) in Teensy 3.5. 
