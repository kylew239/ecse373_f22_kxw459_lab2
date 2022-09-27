### Instructions to use the package launch files

Create the catkin_ws and src directories, and move the package launch files into `src`:
```
touch catkin_ws/src
cd catkin_ws
```

Build the package:
```
catkin_make
```

Navigate to the `src` directory and run the following:
```
source /devel/setup.bash
roslaunch navvis_description navvis.launch
```

### Optional Parameters:

* `use_xacro:=` toggles the use of the xacro file. This is set to false by default, and will accept `true` and `false`
* `publisher_gui:=` toggles the use of the joint-state-publisher-gui. This is set to true by default, and will accept `true` and `false`