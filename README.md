# Depthai ROS Repository
Hi and welcome to the main depthai-ros respository! Here you can find ROS related code for OAK cameras from Luxonis. Don't have one? You can get them [here!](https://shop.luxonis.com/)

You can find the newest documentation [here](https://docs.luxonis.com/software-v3/depthai/ros/)

If your computer is having trouble building, you can specify to the compiler to only do one thing at a time like so:
MAKEFLAGS="-j1" colcon build --executor sequential --parallel-workers 1     --cmake-args "-DCMAKE_BUILD_TYPE=Release"     --packages-select depthai_ros_driver
