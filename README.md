# Basics of mobile robotics
This repository contains multiple resources related to the final project of the course "Basics of mobile robotics" (taught by Professor F. Mondada), attended in the Fall semester of 2021 at EPFL. The project has been done in cooperation with Nay Abi Akl, Mariam Hassan and Alaa Abboud.

The final project consisted in implementing the complete software stack of the Thymio robot (see a simulated Thymio in the picture below, source: [OlivierMichel - Own work, CC BY-SA 4.0](https://commons.wikimedia.org/w/index.php?curid=69693699)) to make it capable of following an optimal path to reach a user-defined goal while avoiding static and dynamic obstacles. Therefore, the project involved path planning, obstacle avoidance, navigation and precise and robust localization.
![simulated Thymio robot](/images/Thymio.jpg)

The following resources are present in the repository:
- [Report](/Report.ipynb), introducing both the ideas and the code at the basis of the project. The different algorithms implemented to achieve path planning, navigation and obstacle avoidance are presented and documented to ensure reproducibility;
- [Images](/images/) and [Env](/env/), presenting all the images which have been inserted in the report, and help explaining the algorithms and the strategy devised;
- [Camera calibration process](/Camera_Calibration_Process.ipynb), which specifies the code used to calibrate the camera.