# URDF_for_delta

Clean Build and Install Directories
```
rm -rf build install log
```
- Build the workspace
```
colcon build --symlink-install
```
- Source the workspace
```
source /opt/ros/humble/setup.bash

```
- run the launch file
```
ros2 launch delta view_robot_launch.py
```
