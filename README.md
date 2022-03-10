# Online Indoor Localization Using DOA of Wireless Signals
## Overview
This repository contains the datasets and scripts used in the experimentation for localization algorithms. Simulation folder contains tested dataset for each trajectory and implmenetd proposed "PF-DOA (Particle Filter Wi-Fi DOA)" indoor localization algrorithm along with state-of-the-art algorithms.
Visualize the system as: 

![Overview](/images/overview.png)
### Simulation
Simulation experimentations taken place for 6 x 6 meter of bounded region where Access Point is placed on the top of the moving robot and wireless sensor nodes places at the fixed positions (corners) which are (0,0), (0,6), (6,0), and (6,6) respectively. Robot followed three different trajectoriers: Inside, Boundary and Diagonal. For each of the trajectory we predicted the position using multiple localization techniques and proposed approach as well.

![Combined Trajectory](/images/combined_trajectories.png).

In the Simulation folder there is a separate python script file for each localization technique.

To execute the script run: `$ python3 <script_file>`

