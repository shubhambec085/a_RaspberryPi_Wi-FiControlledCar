# a_RaspberryPi_Wi-FiControlledCar
Code for wi-fi controlled car using raspberryPi

#Raspberry Pi Robot Remote Control
This project is aimed at controlling a robot using Raspberry Pi GPIO pins via a graphical user interface (GUI) created with tkinter. The script allows users to control the robot's movement in different directions and record a sequence of movements for repeated execution.

#Requirements
Raspberry Pi
Python 3.x
tkinter (included with Python)
RPi.GPIO library


#Usage
Connect the GPIO pins of the Raspberry Pi to the motor driver or controller of the robot. Adjust the pin numbers in the script if necessary.

#Run the script robot_remote_control.py using Python:
python robot_remote_control.py

A tkinter GUI window will open with buttons for controlling the robot's movement. Press the buttons to move the robot in the corresponding direction.

To record a sequence of movements, press the "Repeat" button after performing the desired actions. The recorded sequence will be executed immediately.

Press the "Repeat" button again to clear the recorded sequence and start recording a new one.

Close the GUI window to stop the script.


#GPIO Pin Configuration
The GPIO pins used for controlling the robot's movement are configured in the script. Make sure the pin numbers match the connections to your robot's motor driver.
