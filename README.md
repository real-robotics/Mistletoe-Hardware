# Mistletoe Hardware Open Source Archives

## ⚠️ Under construction... Assembly instructions etc. to come in the future... ⚠️

## Usage 

In each version directory, there is a `Fusion files` `Print files` and `Simulation Files` directory, where `Fusion files` contains the f3d files for the project, `Print files` for the printbeds, and `Simulation Files` for XACRO/URDF/USD files that can be used to simulate the robot.

### ~~3D Printing~~ Printing these well is WIP

3D printing orientations are in the `PRINTBEDS.3mf` file located in each mistletoe hardware release folder.  
You will need to print the items in the HIP and KNEE folder 4 times (4 legs), and the BODY folder 1 time. When there are more than one needed for that module, the stl will have the qty in front of the part name, ie. `2x  tensioner long`.

### Simulation

The simulation files are in the URDF or XACRO format, created using the [fusion2URDF fork by 16cra40](https://github.com/16cra40/fusion2urdf) which it itself is a fork of the original repo by SpaceMaster85. They can be run in rviz, or the simulation software of your choice. To use the URDF in Isaac Lab as we do, please reference the [Mistletoe-Sim](https://github.com/REAL-Robotics-Lab/Mistletoe-Sim.git) repository.

## Other links

- [Mistletoe-cpp Repository](https://github.com/REAL-Robotics-Lab/Mistletoe-cpp.git)
- [Mistletoe-Sim Repository](https://github.com/REAL-Robotics-Lab/Mistletoe-Sim.git)
