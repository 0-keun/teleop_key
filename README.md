# teleop_key


## install
```
cd limo_ws/src
git clone https://github.com/0-keun/teleop_key.git
```
## catkin_make, permission
```
cd ..
catkin_make
cd src/teleop_key/scripts
chmod 775 teleop_key.py
```
## run
```
roscore
```
```
roslaunch limo_base limo_base.launch
```
```
rosrun teleop_key teleop_key.py
```
