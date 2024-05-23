# f1tumth
TUM Pheonix Robotics Project on the f1tenth car

Setup
=====
when cloning use the following comman to also clone the submodules

    git clone https://github.com/LOehler/f1tumth.git --recurse-submodules

Follow the installation procedure for the [simulation](https://github.com/f1tenth/f1tenth_gym_ros.git) and [waterloo code](https://github.com/fjahncke/f1tenth_ws_waterloo.git)

Change all the `ge86bol` in the config paths to your home directory name

that is in the simulation package (f1tenth_gym_ros) `config/sim.yaml`

and in the waterloo code (f1tenth_ws_waterloo) `src/pure_pursuit/config/sim_config.yaml`, `src/rrt/config/sim_config.yaml`, `src/stanley_avoidance/config/sim_config.yaml`

