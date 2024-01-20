# Line-Follower

A line follower robot is a device with the primary function of autonomously tracking a predefined path marked on the ground. 

It has a reflectance sensor underneath, acting like its eyes, that constantly watches for a specific color or contrast, usually a dark line on a lighter surface. As the robot moves along, the sensor communicates with its brain, letting it know where the line is. If the sensor sees the line on the left, the robot adjusts to the left; if on the right, it adjusts to the right. This communication helps the robot make quick decisions to keep itself right on the path, using its wheels to make precise adjustments. 

# How it works

The line follower robots is functioning based on the following principles:

* **Sensor Detection**: The line follower robot is equipped with a reflectance sensor positioned underneath, akin to its eyes, that constantly scans the ground.
* **Contrast Recognition**: The sensor is programmed to recognize a specific color or contrast, typically a dark line on a lighter surface or vice versa, representing the desired path.
* **Continuous Monitoring**: As the robot moves, the sensor continuously monitors the surface beneath and relays information to the robot's brain about the location of the detected line.
* **Decision-Making**: Based on the signals from the sensor, the robot's brain makes real-time decisions. If the line is on the left side, the robot adjusts its course to the left; if on the right, it adjusts to the right.
* **Wheel Adjustments**: The robot has wheels that can move independently. In response to the sensor signals, the robot makes precise adjustments to its wheels, ensuring it stays aligned with the detected line.
* **Autonomous Navigation**: By iteratively adjusting its wheels based on sensor feedback, the line follower robot autonomously follows the designated path without external guidance.

# Components

| Component  | Link |
| ------------- | ------------- |
| Arduino Uno  | https://docs.arduino.cc/hardware/uno-rev3|
| LIPo battery | https://www.techtarget.com/whatis/definition/lithium-polymer-battery-LiPo|
| QRT-8A reflectance sensor  | https://www.pololu.com/product/960|
| L293D Motor Driver | https://www.instructables.com/How-to-use-the-L293D-Motor-Driver-Arduino-Tutorial/  |
| DC Motor | https://www.tutorialspoint.com/arduino/arduino_dc_motor.htm |

# Circuit



