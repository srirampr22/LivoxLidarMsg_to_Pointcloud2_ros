# `livox2pointcloud`

> Converts `livox_ros_driver/CustomMsg` from official ROS livox driver to `sensor_msgs/PointCloud2` for easy visualization in rviz

### Dependencies

* ROS Noetic
* [`livox_ros_driver`](https://github.com/Livox-SDK/livox_ros_driver) (in same workspace)
* [Livox SDK 2.3.0](https://github.com/Livox-SDK/Livox-SDK) installed

### Usage

```bash
rosrun livox2pointcloud livox2pointcloud_node [livox_topic:="/livox/lidar"] [pointcloud_topic:="/livox/pointcloud2"] [frame_id:="base_link"]
```

