Steps to build and run:-
1) Create a catkin workspace and clone/copy this package in the src folder. Example:-  "catkin_ws/src"
2) Build the package from the root folder of catkin workspace with the command "catkin_make".
3) Source the setup.bash files generated as needed for every terminal by ROS.
4) Launch our websocket launch file: roslaunch roslibjs websocket.launch
5) Open the website that we created in the browser of your choice i.e. gui.html
6) You should now see the text “Connected” in our connection status
7) Open another terminal and publish to /txt_msg topic using:- rostopic pub /txt_msg std_msgs/String "data: 'Test message'" -1

Output:-
    The message should appear in the span field that we created for this purpose

