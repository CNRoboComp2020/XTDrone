# XTDrone

<div id="sidebar"><a href="./README.md" target="_blank"><font color=#0000FF size=5px >[中文版]<font></center><a></div>

#### Description

XTDrone is a UAV simulation platform based on PX4, ROS and Gazebo. XTDrone supports mulitrotors (including quadrotors and hexarotors), fixed wings, VTOLs (including quadplanes, tailsitters and tiltrotors) and other unmanned equipment (such as UGVs, USVs and robotic arms). It's convenient to deploy the algorithm to real UAVs after testing and debugging on the simulation platform.

<img src="./images/vehicles.png" width="640"  /> 

Architecture for single vehicle simulation is shown as the below figure.  For more details, see the paper

Xiao, K., Tan, S., Wang, G., An, X., Wang, X., Wang, X.: XTDrone: A Customizable Multi-rotor UAVs Simulation Platform. arXiv preprint **[ arXiv:2003.09700](https://arxiv.org/abs/2003.09700)** (2020)

<img src="./images/architecture_1.png" width="640" height="480" />  

Architecture for multiple vehicle simulation is shown as the below figure.  For more details, see the paper

Xiao, K., Ma, L., Tan, S., Cong, Y., Wang, X.: Implementation of UAV Coordination Based on a Hierarchical Multi-UAV Simulation Platform. arXiv preprint **[ arXiv:2005.01125](https://arxiv.org/abs/2005.01125)** (2020)

<img src="./images/architecture_2.png" width="640" />  

Developers can quickly verify algorithms with XTDrone, such as:

1. Object Detection and Tracking

<img src="./images/human_tracking.gif" width="640" height="360" /> 

2. Stereo SLAM

<img src="./images/vslam.gif" width="640" height="360" /> 

3. RGBD-SLAM

<img src="./images/rgbdslam.gif" width="640" height="360" /> 

4. 2D Laser SLAM

<img src="./images/laser_slam_2d.gif" width="640" height="360" /> 

5. 3D Laser SLAM

<img src="./images/laser_slam_3d.gif" width="640" height="360"/>  

6. VIO 

<img src="./images/vio.gif" width="640" height="360" />  

7. Motion Planning

<img src="./images/motion_planning.gif" width="640" height="360" />  

8. Formation

<img src="./images/formation_1.gif" width="640" height="360" />  

<img src="./images/formation_2.gif" width="640" height="360" />  

9. Fixed wing

<img src="./images/planes.gif" width="640" height="360" />  

10. VTOLs

<img src="./images/vtols.gif" width="640" height="360" />  

11. UGV

<img src="./images/ugv.gif" width="640" height="360" />  

12. USV

<img src="./images/usv.gif" width="640" height="360" />  


#### User manual

 [XTDrone Manual](https://www.yuque.com/xtdrone/manual_en)

#### Developing Team

- Founders: Kun Xiao, Shaochang Tan
- Adviser: Xiangke Wang
- Developers: Kun Xiao, Shaochang Tan, Guanzheng Wang, Lan Ma, Qipeng Wang, Ruoqiao Guan, Xinyu Hu, Keyan Chen, Gao Chen

#### Thanks to Contributers

Changhao Sun, Zihan Lin, Yao He