# ROS2 Version FAST-LIVO2 Workspace

## Usage

```bash
git clone https://github.com/shamanqing1/fast_livox2_ros2.git fast_livo2_ws
cd fast_livo2_ws
mkdir src
vcs import src < ros2.repos
colcon build --cmake-args -DCMAKE_BUILD_TYPE=Release
```