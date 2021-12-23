# Installation
```sh
mkdir -p ~/catkin_ws/src
git clone --depth=1 https://github.com/AkashKarnatak/ar_tag_tutorial ~/catkin_ws/src/ar_tag_tutorial
cd ~/catkin_ws
catkin_make
source ~/catkin_make/devel/setup.bash
roslaunch ar_tag_tutorial world.launch
roslaunch ar_tag_tutorial spawn_ar_tracking.launch
```
