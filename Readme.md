# Demo Robot Model RE604 Courses

## How to Run the Simulation

**1. Create ROS Workspace**

```bash
mkdir -p pan_tilt_ws/src
cd pan_tilt_ws/src
git clone https://github.com/ekorudiawan/pan_tilt_description.git
```

**2. Build and Test Run**

```bash
cd pan_tilt_ws
catkin_make
source devel/setup.bash
roslaunch pan_tilt_description pan_tilt_rviz.launch
```