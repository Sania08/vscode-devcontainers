# vscode-devcontainers
Devcontrainer files

```mkdir src && cd src```

clone these repos:

```git clone https://github.com/yujinrobot/kobuki_core.git```

```git clonehttps://github.com/turtlebot/turtlebot.git```

```git clone https://github.com/turtlebot/turtlebot.git```

```cd ..```

```catkin_make```

```rosrun kobuki_ftdi create_udev_rules```

```source devel/setup.bash```

```roslaunch turtlebot_buildup minimal.launch```

```roslaunch turtlebot_teleop keyboard_teleop.launch```


