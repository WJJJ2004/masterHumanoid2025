# IEEE 2025 Robit Humanoid urdf for RL walk
--- 
### masterHumanoid_discription 
- build mesh in ROS2 WS
```bash
cd ~/colcon_ws/src
git clone https://github.com/WJJJ2004/masterHumanoid2025
colcon build packages-select masterHumanoid2025 
```

- RVIZ2 Test
```bash
source ~/.install/setup.bash
ros2 launch masterHumanoid2025 display.launch.py
```

### masterHumanoid2025.urdf
- Fix mesh link  before import urdf
