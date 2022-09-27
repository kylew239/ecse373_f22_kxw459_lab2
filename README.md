### Instructions to use the package launch files

In terminal, create the catkin_ws and src directories, and move the package launch files into `src`:
```
touch catkin_ws/src
cd catkin_ws
```

Run 'catkin_make' to build the package

Navigate to the `src` directory and run the following:
```
source /devel/setup.bash
roslaunch navvis_description navvis.launch
```