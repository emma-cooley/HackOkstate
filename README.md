# HackOkstate
The KY-028 Digital Temperature Sensor measures temperature changes based on thermistor resistance. This module has both digital and analog outputs, there’s a potentiometer to adjust the detection threshold on the digital interface.


Connect the board’s analog output (A0) to pin A0 on the Arduino and the digital output (D0) to pin 3.

Connect the power line (+) and ground (G) to 5V and GND respectively.

When the temperature threshold is reached, the digital interface will send a HIGH signal turning on the LED on the Arduino (pin 13). Turn the potentiometer clockwise to increase the detection threshold and counter-clockwise to decrease it.
