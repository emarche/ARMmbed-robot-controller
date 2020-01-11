# Lightspark, a custom mobile robot built on ARMmbed

This repository contains a backup of the bluetooth controller for Lightspark, a custom mobile robot built on ARMmbed.


<p float="center">
  <img src="/Images/robot.png" width="300" />
</p>

### Controlling Options

The main implementation for this robot, aside from its construction, regards the controlling system.
In particular, three different controllers have been developed:

* Autonomous Navigation: exploiting the ultrasonic sensors, the robot navigates randomly in the environment
* Bluetooth Android Navigation: a human navigation system, designed with an android app
<p float="center">
  <img src="/Images/controller_app.png" width="300" />
</p>
* LeapMotion Controller: a Unity3D application exploits a LeapMotion and a basic interface, to allows a human operator, the control of the robot; here is a demo video: https://www.youtube.com/watch?v=Up212kO3EwQ&feature=youtu.be

## License

- **MIT license**
