# ArduinoCANTestBench
A testbench that uses an Arduino Uno in conjunction with a Seeed Studio CAN Shield to throw CAN frames that contain values from analog inputs.  

## Required Parts
Arduino Uno  
Seeed Studio CAN Shield v2.0  

## Usage Instructions
Before using, be sure to connect the P1 pads on the back of the CAN shield. This toggles the 120 ohm terminating resistor required for CAN implementations.  
Then, simply mount the shield, build and flash this code, and you should be good to go.  
By default, a potentiometer (pin A0) and joystick (pins A1, A2, A3) are used. These can be swapped out for any other analog sensor/system.  
Connect CAN_H and CAN_L to the correct ports on the shield, and you should be good to go.
