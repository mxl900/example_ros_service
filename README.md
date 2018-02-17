# example_ROS_service
This simple example shows how to write a ROS service node.  See the accompanying document, "Introduction to ROS services"

Using service-client interaction to guide the robot to the upper left corner of the map by sending out a string of poses. Meanwhile, the current location and turning angle will be modified to best fit the expectation.

## Running tests/demos

Run the client node with:

`rosrun example_ros_service path_client`

Run the service node with:

`rosrun example_ros_service path_service2`
