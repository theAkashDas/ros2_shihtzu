# ROBO DOG using ROS2

#### 0.0.1
- Added the previous codes.

#### Creating the workspace
```
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
cd ~/ros2_ws
colcon build
source install/setup.bash 
```
#### Creating the package
```
cd ros2_ws/src
ros2 pkg create --build-type ament_cmake robodog
cd ..
colcon build --packages-select robodog
source install/setup.bash
```

