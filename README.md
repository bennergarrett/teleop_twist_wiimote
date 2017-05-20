# teleop_twist_wiimote
Generic Keyboard Teleop for ROS
#Install

To run: `sudo apt-get update`

        `sudo apt-get install python-cwiid`

#Launch
To run: `rosrun teleop_twist_wiimote teleop_twist_wiimote.py`

#Usage
```
Reading from the keyboard  and Publishing to Twist!
---------------------------
Moving around:
   u    i    o
   j    k    l
   m    ,    .

For Holonomic mode (strafing), hold down the shift key:
---------------------------
   U    I    O
   J    K    L
   M    <    >

t : up (+z)
b : down (-z)

anything else : stop

q/z : increase/decrease max speeds by 10%
w/x : increase/decrease only linear speed by 10%
e/c : increase/decrease only angular speed by 10%

CTRL-C to quit
```

