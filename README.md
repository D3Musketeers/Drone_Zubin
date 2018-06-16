# Drone_Zubin

All Qquadcopter related code by Zubin

# 1. ESC Callibration using Arduino
Reference (http://www.techmonkeybusiness.com/esc-calibration-using-an-arduino.html)<br />
Modified above code to achieve callibration and testing of 4 esc's. After the callibration of all the 4 esc's the motor will run for 50% of throttle indefinitely. <br />
Please refer to the website (or ESC-Single_Calibration_Circuit-sml.png) for circuit connections.<br /><br />




# 2. 2D_Gyro_Testing_MPU6050
Testing MPU6050 for Pitch and  Roll only using Putty

This code is a modified version of Jeff Brokking's 2d IMU using LCD display.(http://www.brokking.net/imu.html).<br />
This code is modified to substitute LCD with Putty or any serial monitor. The default Arduino serial monitor is not great for refreshing sensor data. Putty is a better monitor tool.<br />
Download Putty from (https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html).<br />
Install and open in Serial connection type. Mention the exact serial port (Arduino COM port) and baud rate (57600).<br />
Couldn't get multiline display to work. This is single line display for pitch and roll.<br />
