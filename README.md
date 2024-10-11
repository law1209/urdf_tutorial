# urdf_tutorial: Learning URDF Step by Step

 1. [Building a Visual Robot Model with URDF from Scratch](https://wiki.ros.org/urdf/Tutorials/Building%20a%20Visual%20Robot%20Model%20with%20URDF%20from%20Scratch) - Learn how to build a visual model of a robot that you can view in Rviz

## One Shape
    roslaunch urdf_tutorial display.launch model:='$(find urdf_tutorial)/urdf/01-myfirst.urdf'
## Multiple Shapes
    roslaunch urdf_tutorial display.launch model:=urdf/02-multipleshapes.urdf Multiple Shapes
## Origins
    roslaunch urdf_tutorial display.launch model:=urdf/03-origins.urdf 
## Material Girl
    roslaunch urdf_tutorial display.launch model:=urdf/04-materials.urdf
## Finishing the Model
    roslaunch urdf_tutorial display.launch model:=urdf/05-visual.urdf

 2. [Building a Movable Robot Model with URDF](https://wiki.ros.org/urdf/Tutorials/Building%20a%20Movable%20Robot%20Model%20with%20URDF) - Learn how to define movable joints in URDF

    roslaunch urdf_tutorial display.launch model:=urdf/06-flexible.urdf

 3. [Adding Physical and Collision Properties to a URDF Model](https://wiki.ros.org/urdf/Tutorials/Adding%20Physical%20and%20Collision%20Properties%20to%20a%20URDF%20Model) - Learn how to add collision and inertial properties to links, and how to add joint dynamics to joints.

## Collision
## Inertial
## Joint Dynamics
    roslaunch urdf_tutorial display.launch model:=urdf/07-physics.urdf

 4. [Using Xacro to Clean Up a URDF File](https://wiki.ros.org/urdf/Tutorials/Using%20Xacro%20to%20Clean%20Up%20a%20URDF%20File) - Learn some tricks to reduce the amount of code in a URDF file using Xacro
    
    roslaunch urdf_tutorial display.launch model:=urdf/08-macroed.urdf.xacro


See also [urdf_sim_tutorial](https://github.com/ros/urdf_sim_tutorial) for the final tutorial: [Using a URDF in Gazebo](https://wiki.ros.org/urdf/Tutorials/Using%20a%20URDF%20in%20Gazebo) - Preliminary tutorial on how to spawn and control your robot in Gazebo.
