Repository for storing models of HUBO as well as URDFs describing it for usage with the [DART](https://github.com/golems/dart) simulator.

# Organization

Each robot `$ROBNAME` has
* `$ROBNAME.urdf`: a URDF describing the robot's kinematics and dynamics
* `$ROBNAME-empty-world.urdf`: a URDF describing a simulation world that contains only that robot
* `$ROBNAME-dae`: a directory containing the robot's models

# How to use

Use git submodules to include these models in your own project. This will allow you to easily keep your models up-to-date while maintaining a fixed path relative to the URDFs you write that use them.
