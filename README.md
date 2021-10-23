# traj_controller
ardupilot port for mavros_controllers

Launch the Simulation with iris
```sh
roslaunch launcher simulation_launch.launch
```
Launch arduilot SITL
```sh
sim_vehicle.py -v ArduCopter -f gazebo-iris --console
```
Launch Mavros
```sh
roslaunch iq_sim apm.launch
```
Launch Mavros_controllers
```sh
roslaunch launcher controller_launch.launch
```




