## TeamCode Module

Welcome! This is the home of most of the code I wrote for the FIRST Tech Challenge team FIX IT 3491!

### gamecode
The gamecode package contains the code that directly operates the robot. It relies on the rest of the TeamCode package to work.

### newhardware
The newhardware package is responsible for interfacing with the motor controllers, servo controllers, and the sensors. Besides the I2C sensor interface, it's fairly high-level programming. The low-level interactions (that directly deal with the electronics) are handled by other people.

It also contains the code to use the TrackBall sensor, that we designed and 3D-printed to help with our robot's localization.

### opmodesupport, robots
These packages are here to help make programming the "gamecode" classes much simpler and more readable. The "robots" classes each represent a real-life robot (that our team built) and contains all the functions and objects required to interact with it.

### roboticslibrary, util
Miscellaneous classes used to support "gamecode". They range of a threadpool manager (TaskHandler) to a wiffle ball detector (CircleDetector) to a Android camera interface. 
