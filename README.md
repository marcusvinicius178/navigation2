# Relevant Links to fix our issue with Velodyne communication:

[Real Robot with NAV2 and Lidar](https://www.youtube.com/watch?v=jkoGkAd0GYk)

[Mapping without a Previous Map](https://www.youtube.com/watch?v=dDODrSy6cYU)

[SLAM Toolbox Documentation](https://github.com/SteveMacenski/slam_toolbox)

[Slam_toobox mapping tutorial](https://www.youtube.com/watch?v=rZOxPGCn4QM)

Framework Communication of SLAM

![This is an image](https://raw.githubusercontent.com/SteveMacenski/slam_toolbox/ros2/images/slam_toolbox_sync.png)

There is a video tutorial of VLP 16 usage for mapping on Rviz, take a look:

[Mapping with VLP-16](https://www.youtube.com/watch?v=Ium_J1K-Lxk)

![This is an image](https://github.com/marcusvinicius178/navigation2/blob/galactic/mapping_Slam.png)

# GABRIEL: Files which we have added:

[velodyne launch file](https://github.com/marcusvinicius178/navigation2/blob/galactic/nav2_bringup/bringup/launch/velodyne_test_launch.py)

## Commands we need to run to start velodyne simulation

### Launch Velodyne Driver
'''
ros2 launch velodyne velodyne-all-nodes-VLP16-launch.py
'''
### Open LaserScan or Velodyne PCD data (set velodyne to fixed frame)
'''
ros2 run rviz2 rviz2 -f velodye
'''
### Running the velodyne along NAV2 launch file
ros2 launch nav2_bringup velodyne_test_launch.py







