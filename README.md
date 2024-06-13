# susan_moveit

## 1. Prerequisites
* Install [susan_description](https://github.com/0nhc/susan_description)

## 2. Installation
```sh
cd <your_ws>/src
git clone https://github.com/0nhc/susan_dmoveit
cd ..
rosdep install --from-path src --ignore-src -r -y
catkin_make
```

## 3. Demo
```sh
roslaunch susan_moveit demo.launch
```