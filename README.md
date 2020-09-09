# KUBOT ROS Kinetic Android APP

![](https://img.onl/ZLiQM0)

>KUBO APP can control ROS kinetic robots. Include view 2D grid map, to set navigation, live image , analog joystick to remote control robot and so on.

# 1. Install APK
Download this package, then put kubot_app.apk into the phone and install it. If you don't know how to install apk, please read [this](https://sites.google.com/site/lohos2nchu/shou-jiapp-ying-yong/install-apk-apps).

# 2. How to use
1. Connect Android phone wifi to KOBOT robot.
2. Open this app, enter ros master ip. 

3. After clicking the connection, you can see the picture below



>Press and hold the map mode to switch. Press and drag the white blocks in the map to perform functions

![#f03c15](https://placehold.it/20/f03c15/000000?text=+) RED FRAME : 

The lidar SLAM map created by KOBOT robot. The black dots are obstacles, walls, etc., the white areas are walkable places, and the gray areas are unknown areas.

![#c5f015](https://placehold.it/20/c5f015/000000?text=+) GREEN FRAME:

Remote control handle. You can click and drag to remotely control the car. The remote control handle has a speed percentage. It is recommended to control the remote control mode at 50%. Push it slowly or lightly press it to gr
een to rotate in place.

![#1589F0](https://placehold.it/20/1589F0/000000?text=+) BLUE FRAME : 

The live picture returned by the cams. If no cams is installed than nine circles will be displayed.

![#1589F0](https://placehold.it/20/FFFFF/000000?text=+) YELLOW FRAME : 

The Set Goal mode is to release the position to go to for the automatic navigation. By pressing and rotating, you will see another arrow. The position of the arrow on the map and the direction to guide it is for the KUBOT car to automatically go to the position and attitude .


The Set Pose mode is to redefine the position of the car on the map. If it is used for a long time, interfered by external forces, or the ground is uneven, it may cause the map to shift, and the KUBOT car will not know the actual position, causing the car to enter a trek. Use this mode to reset the position of the car on the map.
