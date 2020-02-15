The following tutorials should be followed in the given order below. This would ease the understanding of general tool/techniques necessary for robotics with ROS in general.
These steps should serve as a building block for understanding any packages, which are not in the scope of this list.

# Always clone the melodic branch whenever possible

**Purpose of 1 - 4: ros, transformations, understand a basic URDF, manipulation and planning with moveit**
1. [ros_tutorial](https://github.com/ros/ros_tutorials)

2. [tf_tutorial](http://wiki.ros.org/tf/Tutorials) and [tf_tutorial_code](https://github.com/ros/geometry_tutorials) tf is sufficient. If interested proceed to tf2.

3. [urdf_tutorial](http://wiki.ros.org/urdf/Tutorials) and [urdf_tutorial_code](https://github.com/ros/urdf_tutorial)

4. [moveit_tutorial](http://docs.ros.org/melodic/api/moveit_tutorials/html/index.html) Do the tutorial until [pick_and_place](http://docs.ros.org/melodic/api/moveit_tutorials/html/index.html#using-moveit-directly-through-the-c-api). And the [moviet_tutorial_code](https://github.com/ros-planning/moveit_tutorials/tree/melodic-devel)
clone the melodic branch
```sh
$ git clone -b melodic-devel https://github.com/ros-planning/moveit_tutorials
```
