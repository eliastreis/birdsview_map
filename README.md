# birdsview_map
This package can be used to create a bird view 2D occupancy map of your gazebo world. This way obstacles above the robot hight can be included in the map.

# Usage

1. Install the following dependent packages as well as the `requirements.txt`.

- [gazebo_ros_2Dmap_plugin](https://github.com/marinaKollmitz/gazebo_ros_2Dmap_plugin)
- [map_server](http://wiki.ros.org/map_server)

2. Move your gazebo `.world` file in den **world** folder.

3. Run the following command and specify the following parameter: 
   
    **target_hight**: Up to which obstacles should be taken into account

```bash
roslaunch birdsview_map create_map.launch target_hight:=2
```

4. Find the final map in the **final_map** folder

# ToDo 
- create pedsim-map