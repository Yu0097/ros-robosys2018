# ros-robosys2018

# Overview
PCからweb上にデータ（数値）を送り、表示する。

# Description
rosbridgeを使いパブリッシャ(count_py)からパブリッシュされた数値をweb上に送り、表示する。

# Demo
https://youtu.be/y3gYapzfpfM


# Requirement
* Computer
  * PC
* OS
  * Ubuntu16.04.5(VirtualBox上で可)

* ROS kinetic kame


# Install
```
$ git clone https://github.com/Yu0097/ros-robosys2018.git
```

# Usage
```
$ roslaunch ros-robosys2018 ros-robosys2018.launch
```
IPアドレスの確認
```
$ ip a
```
ブラウザで「http://IPアドレス:8000」を開く


# License
GNU General Public License v3.0
