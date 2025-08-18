# Notice  
The URDF is likely not oriented correctly (correct would be +x is forward, +y is left, +z is up) due to differences in defining axes in Fusion vs. URDF. Please check before using. The USD file however has been updated to follow the proper orientation.  

To build and install the ROS package (which should not be neccesary), run `colcon build` and then `source install/setup.bash` from the `mistletoe-v4_description` directory. 