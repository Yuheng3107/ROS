# REDesign Robot Arm Feeder
## OS To Use
Ubuntu 20.04, can run on a VM
## Install ROS1
````
wget -c https://raw.githubusercontent.com/qboticslabs/ros_install_noetic/master/ros_install_noetic.sh && chmod +x ./ros_install_noetic.sh && ./ros_install_noetic.sh
````

Make sure to activate env and install deps



To fix bug with cannot find lib:
sudo ln -s /opt/ros/noetic/lib/aarch64-linux-gnu/* /opt/ros/noetic/lib/

To load env variables run
````
source ./env_backup.sh
````
