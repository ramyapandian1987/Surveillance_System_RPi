# Surveillance_System_RPi

This surveillance code switches the camera on whenever it senses the motion of an object and alerts the user with an email notification with a recorded video in mp4 file format.

#### Materials Needed:

##### Hardware:

1.	Raspberry Pi 4

2.	PIR module

3.	UC261 – Camera module

4.	Breadboard

5.	GPIO Extension Board

6.	2 Male-to-Male jumper cables

7.	3 Male-to-Female jumper cables


##### Software:

1.	Raspberry Pi OS installed

2.	Python 3

3.	sudo apt-get install python-picamera

4.	sudo apt-get install python3-picamera  # if running under python3

#### Setup Instructions:

Note: This is assuming you have installed Raspberry Pi and Python already

Connect RPi, PIR Sensor and Camera module as shown below.

•	VDD to pin 2 of RPi 4

•	GND to pin 6 of RPi 4

•	DOUT to pin 11 of RPi 4
 
![image](https://user-images.githubusercontent.com/37421836/167173122-26d8121c-68fc-4dd1-8819-96d0e2c8008b.png)


#### To execute – 

The code is available on GitHub at https://github.com/ramyapandian1987/Surveillance_System_RPi/blob/main/surveillance-code.py

1.	Download the code and execute as shown below – 

Python3 surveillance-code.py

###### Note - create a folder named "capture" in the same path where the code resides

