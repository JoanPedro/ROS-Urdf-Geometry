# ROS-Urdf-Geometry
World configurate and Test for URDF definitions

# Setup:

The exact location of ROS packages is unimportant, as long as they are in the src space of your workspace. Make use of that, by placing the new packages directly in the src space, instead of in a sub directory.

Extract the contents of the file into $HOME/hrwros_ws/src.

Always overwrite all the previous content!

After the above step, your folder structure under $HOME/hrwros_ws/src should look like this:

    hrwros
            hrwros_week1
            hrwros_msgs

    hrwros_support
    hrwros_week2

Now run the following commands in the CCS terminal:

```
  source /opt/ros/melodic/setup.bash
  cd $HOME/hrwros_ws
  catkin clean -y
  catkin build
  source $HOME/hrwros_ws/devel/setup.bash
```

At this point you are all setup to continue use the CCS as normal.

```javascript
~/hrwros_ws/src/hrwros_support/urdf> roslaunch hrwros_support visualize_hrwros.launch
```

**Obs:** For use this setup you need to configure your ROS ambient following: https://github.com/JoanPedro/ROS-Ambient-Setup
