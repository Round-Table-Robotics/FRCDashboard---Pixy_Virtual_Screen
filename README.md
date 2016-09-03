#Pixy Virtual Screen
Our Team uses the Pixy as a way to cameratrack objects and because it has no live feed we use the variables it outputs to simulate a live feed. Becasue it only uses the variables it gives us it has very little detail. But it is helpful none the less.

##Changes
Relocated the Widgets
Added a Switch for Device Input (Between Virtual Pixy Screen and a Network Cam)


##Virtual Pixy Screen
![Image of The Virtual Screen](https://github.com/Round-Table-Robotics/FRCDashboard---Pixy_Virtual_Screen/blob/master/Virtual%20Display.PNG?raw=true)
The green rectangles are targets that are picked up by the Pixy and sent to the dashboard after I test the Program on a Roborio I will be adding a connetion indicator insted of the green rectangles setup like a goal.

##Network Cam Screen
![Image of The WebCam Screen](https://github.com/Round-Table-Robotics/FRCDashboard---Pixy_Virtual_Screen/blob/master/WebCam.PNG?raw=true)
The BB-8 is an example of a Network Cam you can change the location of your network cam in the Index.html I suggest that you use mDNS so you can easily find the Camera or Device on the FMS or network that you are using. as you can see I am using PI1792.local:443 that is the custom address set from the mDNS the PI1792 is from the name of the device on the network. If you want to stream Video without a network cam I recommend a webcam and a raspberry pi using [MotionEye](https://github.com/ccrisan/motioneye).

## FRC Dashboard
FRC Dashboard is a fully customizable dashboard for [FIRST Robotics Competition (FRC)](http://firstinspires.org/robotics/frc) which is based on web languages (JavaScript/CSS/HTML). It's completely legal for competition, and can be used to give your whole drive team significantly richer control of your robot.

The dashboard's code is designed to be 100% accessible, tweakable, and expandable. To help in this aim, the code is rigorously documented with thousands of inline comments and [a set of training exercises](https://github.com/FRCDashboard/training). In addition, the base system comes with several functioning example widgets and features, and [many addons](https://github.com/FRCDashboard?query=addon-) have been created to speed up the development of your team's dashboard.

## Authors of FRCDashboard
* [Erik Boesen](https://github.com/ErikBoesen) is the primary developer of FRC Dashboard.
* [Team 1418](https://github.com/frc1418) used earlier versions of this code in 2015 and 2016.
* [Leon Tan](https://github.com/lleontan) led the original 1418 UI team, coded pynetworktables2js, and developed a browser-based UI which was years later reworked to create FRC Dashboard.
* [Dustin Spicuzza](https://github.com/virtuald) leads the [RobotPy](https://github.com/robotpy) project mentored team 1418 through much of FRC Dashboard's genesis.
