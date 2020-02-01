# HAMER_mini v0.1 - (Released 28-01-2020)
The HAMER_Mini robot package is designed as a sub-version of the "Halikarnas Modular Educational Robot" main model. ROS Melodic is compatible.

For HAMER main model : https://github.com/Akerdogmus/hamer

Rviz Launching:

    $ roslaunch hamer_mini hamermini_rviz.launch model:=hamer_mini.urdf
    
Gazebo Launching:

    $ roslaunch hamer_mini hamermini_gazebo.launch

NOTE: "master" branch is released version (v0.1) of HAMER_mini robot. All versions of the robot are available on branches.

------------------------------------------------------------------------------
# HAMER_mini v0.2

Changelog v0.2 - (29-01-2020)
-----------------------------
- Ultrasonic sensors added.

Requirements:

- In order for the sensors to work properly, "gazebo_ros_pkgs" files must be downloaded.

        $ cd ~/hamer_mini/src
        $ git clone https://github.com/ros-simulation/gazebo_ros_pkgs.git -b melodic-devel

----------------------------------------------------------------------------------
# HAMER_mini v0.3

Changelog v0.3 - (31-01-2020)
---------------------------

-   Added "gazebo_ros_control" to hamer_mini's urdf file.
-   Changed ultrasonic sensors positions and quantities.

-------------------------------------------------------------------------------------
# HAMER_mini v0.4

Changelog v0.4 - (01-02-2020)
------------------------------

-   Available SLAM package usage (hamermini_slam.launch).
-   Added laser sensor.
-   Available mapping with laser sensor to gazebo maps.

Requirements:

- In order for the SLAM to work, "slam_gmapping" package must be downloaded.
    
        $ cd ~/hamer_mini/src
        $ git clone https://github.com/ros-perception/slam_gmapping.git -b melodic-devel

SLAM Launching:

        $ roslaunch hamer_mini hamermini_slam.launch

------------------------------------------------------------------------------------------

Contributors: Alim Kerem Erdoğmuş
