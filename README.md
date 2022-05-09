# utbm_simulation

This repository regroup UTBM's worlds used for simulation.

These worlds have been build based on building's map. So you can rely on them expect for the furniture.

# Install 

```
cd catkin_ws/src
git clone https://github.com/Thermay-Robotics/utbm_simulation.git
cd .. && catkin_make
```

# Launch world

To launch a world, follow this instructions: 
```
export TURTLEBOT3_MODEL=burger
roslaunch utbm_empty_world utbm_empty_world.launch
```
After that, you can do whatever you want (slam, teleop,...).

## Issues you can have

When updating or creating a world you may face difficulties to save your world. The page is freezing. To overcome this, you can minimize and maximize the gazebo page or run it sudo.

Another issue you may face concerns world’s stuff. If nothing is display on the screen when launching file, please add an issue to the repository and to quick fix it on your side, you can copy paste models folders to ```
 ~/.gazebo/models``` folder.

### Ressources

Tutorial to learn how to create world :
- https://www.generationrobots.com/blog/en/robotic-simulation-scenarios-with-gazebo-and-ros/

