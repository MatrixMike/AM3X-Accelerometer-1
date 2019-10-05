 3 Axis Accelerometer Smoothing

 20 samples to keep track of. The higher the number, the
 more the readings will be smoothed, but the slower the output will respond to
 the input. Using a constant rather than a normal variable lets us use this
 value to determine the size of the readings array.
 when changes to the Avergae Serial data is sent to the COM port to be read and LED changes state
 
 Hardware Setup
 
 Arduino UNO
 LED on digital pins A5, A6, A7
 Freetronics AM3x (XC4226)Accelerometer Module 3 Axis +/- 1.5g, +/-6g
 3 Axis Accelerometer on analog pins x = 0, Y = 1, Z = 2, 3.3v, GND
