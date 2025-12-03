Read Me:

1) Download the mobile_robot package and place it in the src folder of the workspace.
2) Navigate to workspace_ws/src folder and run the command svn export https://github.com/shantanuparabumd/ENPM-662-Introduction-to-Robot-Modelling.git/trunk/templates/plugin/odometry
3) cd .. and colcon build
4) To observe the goal navigation run the following commands in seoarate terminals.
   $ ros2 launch mobile_robot gazebo.launch.py
   $ ros2 run mobile_robot auto_mission.py 

5) To observe the pick and place, run the following commands.
   $ ros2 launch mobile_robot simulation_world.launch.py 
   $ ros2 run mobile_robot auto_mission_3.py
