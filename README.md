# Server17
Is a java class designed to stream two USB cameras (or other video sources) to the FRC DS on a single CameraServer Stream<br>
This class is designed around the 2017 version of FIRST Robotics WPILIB v2017.3.x +<br>
This allows teams to use a dual camera setup without using multipule CameraServer widgets, or while using the default dashboard.<br>
The active camera can be changed by simply calling the<br> <code>Server17.switchCameraTo(String) </code> <br>possible arguments are: "front" and "back".<br>
NOTE: this does not literally display two streams in the same space at the same time. <br>
This code allows teams to switch what camera the robot is sending to the dashboard, and display multiple different streams at different times, in the same widget.
