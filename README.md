# Extra Files to Robotics Projects

In this repository, there are extra files to install and use some projects

# Robotica Movel

In this folder, there are the files to complete the installation of [MRS system](https://github.com/ctu-mrs/mrs_uav_system) with [Challenge_Petrobras package](https://github.com/LASER-Robotics/Petrobras_Challenge) and [mobile robotic class from UFSCar](https://github.com/lidiaxp/robotica_movel). To access the complete tutorial enter [here](https://www.laris.ufscar.br/pt-br/pessoal/simulator-mrs).

# Solve "reference validation failed"

If this error appear when you run some package cited in this package, you need replace the file "control_manager.cpp" presents in ~/mrs_workspace/src/uav_core/ros_packages/mrs_uav_managers/src for the same file on [robotica_movel](https://github.com/lidiaxp/extraFilesRobotics/blob/main/Robotica%20Movel/control_manager.cpp).

# Add Hokuyo

To add hokuyo and use in simulations using [Challenge_Petrobras package](https://github.com/LASER-Robotics/Petrobras_Challenge) or [mobile robotic class from UFSCar](https://github.com/lidiaxp/robotica_movel) based on [MRS system](https://github.com/ctu-mrs/mrs_uav_system), you will need replace the codes presents in hokuyo_robotica_movel in the same place at the package (~/mrs_workspace/src/simulation/ros_packages/mrs_simulation/models/mrs_robots_description/urdf). In this case, was add the sensor hokuyo only to F-450.
