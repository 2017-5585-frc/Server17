# Server17
Is a java class designed to stream two USB cameras (or other video sources) to the FRC DS on a single CameraServer Stream<br>
This class is designed around the 2017 version of FIRST Robotics WPILIB v2017.3.x +<br>
This allows teams to use a dual camera setup without using multipule CameraServer widgets, or while using the default dashboard.<br>
The active camera can be changed by simply calling the method<br> <code>Server17.switchCameraTo(String) </code> <br> from any command or other method<br>
possible arguments are: "front" and "back".<br>
NOTE: this does not literally display two streams in the same space at the same time. <br>
This code allows teams to switch what camera the robot is sending to the dashboard, and display multiple different streams at different times, in the same widget. <br>
This is a BASIC implementation of the camera server class, and as such, is mostly an implementation of FIRST code. it is intended as an example of how to use the new CameraServer code, not an origninal design, and should not be considered as such. <br>
<br>
FIRST Team 5585<br>
  (TechValley Region)
