# Mistletoe Hardware Open Source Archives

## ⚠️ Under construction... Assembly instructions etc. to come in the future... ⚠️

## Usage 

In each version directory, there is a `fusion_files` `print_files` and `sim_files` directory, where `fusion_files` contains the f3d files for the project, `print_files` for the printbeds, and `sim_files` for XACRO/URDF/USD files that can be used to simulate the robot.

### ~~3D Printing~~ Printing these well is WIP

3D printing orientations are in the `PRINTBEDS.3mf` file located in each mistletoe hardware release folder.  
You will need to print the items in the HIP and KNEE folder 4 times (4 legs), and the BODY folder 1 time. When there are more than one needed for that module, the stl will have the qty in front of the part name, ie. `2x  tensioner long`.

### Simulation

The sim_files are in the URDF or XACRO format, created using the [fusion2URDF fork by 16cra40](https://github.com/16cra40/fusion2urdf) which it itself is a fork of the original repo by SpaceMaster85. They can be run in rviz, or the simulation software of your choice. To use the URDF in Isaac Lab as we do, please reference the [Mistletoe-Sim](https://github.com/REAL-Robotics-Lab/Mistletoe-Sim.git) repository.

### Joint and Link Naming Convention  
Should be revised at another time because of how awful it is.
![robot naming convention](docs/awful%20naming%20convention.png)


### Robot Orientation
![robot orientation](docs/mistletoe%20orientation.png)


## Other links

- [Mistletoe-cpp Repository](https://github.com/REAL-Robotics-Lab/Mistletoe-cpp.git)
