# Where Am I? #
#### Robotics Software Engineering ####
#### Term 2 ####
#### Project 2 ####

_Concepts/Skills Learned:_
  * C++
  * Kalman filters: 1-D, milti-dimensional, extended (with TurtleBot)
  * Monte Carlo Localization: Bayes filtering
  * ROS: amcl package, navigation stack

---

_Project Description:_

This particular project first introduced interaction with ROS via a C++ interface, the preferred language type for real-life robotics applications. Both Kalman filters and Monte Carlo particle filters were taught, with the latter chosen for this localization project. Furthermore, this project introduced the full process for robot creation within the ROS framework. Using XML format, a URDF file was created for a basic two-wheeled robot model, outfitted with camera and laser rangefinder sensors and integrated with both Gazebo and Rviz. Said robot was placed within a pre-made Gazebo environment, with the overall project goal being to use the AMCL ROS package for accurate localization. The robot's localization ability was tested by setting specific navigation goals within the maze-like Gazebo environment.

As an additional challenge, a second, more detailed custom robot was modeled and outfitted with sensors. This robot was also linked to both Gazebo and Rviz, having its own AMCL parameters tuned for successful localization and subsequent navigation.

     
   For a full report of how this was accomplished, see the included write-up: 
   
   [Where Am I? Write-Up](https://github.com/akompaniyets/Where-Am-I-AMCL/blob/master/Project%202%20Report.pdf)
