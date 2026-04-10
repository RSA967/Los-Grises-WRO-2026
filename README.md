# Los-Grises-WRO-2026

Official repository of Team Los Grises for the **Future Engineers - World Robot O1ympiad 2026**.
<div align="center">
<img width="1000" height="500" alt="team-image" src="https://github.com/RSA967/Los-Grises-WRO-2026/blob/9e32aee27e9ebda8a6da08e632b9680e6d41e43a/LOS_GRISES_1.webp" />
</div>

Our robot's code is divided into several parts (modules) that help the robot function correctly and interact with the real world. Each module has a different function, but they all work together.

One of the most important modules is the camera module, where we use the "HuskyLens" sensor. This sensor acts as the robot's "eyes," as it can recognize colors. Thanks to this, the robot can detect objects that have been previously trained and obtain information such as their position (X and Y) and size (width and height).

Another module controls the program's operation. This module makes the robot constantly check if it detects any objects. It also includes a button that allows the program to be stopped when necessary.
We also have the data processing module. Here, the robot takes the information it receives from the camera and stores it in variables. For now, this data is displayed on the screen, but later it can be used by the robot to make decisions, such as moving toward an object and/or avoiding it.

The code relates to the robot's electromechanical components, such as the motors, the controller, and the sensors. The motors allow the robot to move, and the controller regulates the power they receive. Although the motors are not directly controlled in this code, the camera's information will be used later to determine how to move.

To use the code, we first write it in the robot's programming environment, then review and compile it to ensure it is error-free.

Finally, it is uploaded to the robot's controller using a USB cable. Once uploaded, the robot can run the program and begin detecting objects.

In conclusion, this code allows the robot to perceive its surroundings using the camera and is the foundation for future automated movement and decision-making.
