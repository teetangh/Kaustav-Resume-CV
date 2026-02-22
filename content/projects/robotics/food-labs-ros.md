# Food Labs Robotics Startup Competition — ROS Engineer

**Type:** Startup interview / competition project
**Timeline:** ~2020
**Repository:** `github.com/teetangh/Kaustav-ROS-Workspace` (models & simulations)
**Also:** `github.com/teetangh/FoodLabs-ROS-Startup-Competition`

---

## Summary

Comprehensive ROS robotics project for a startup interview/competition. Involved designing, modelling, and simulating robots and sensors across multiple platforms, and implementing autonomous navigation.

---

## Key Deliverables

### 3D Modelling & Environment
- Designed, modelled, constructed, and assembled sensors and robots across freeCad, Blender, and Gazebo
- Fabricated a hotel/defense building from floorplan using Gazebo World Editor

### Velodyne HDL-32 Sensor
- Created an SDF model of the Velodyne HDL-32 LiDAR sensor
- Improved model appearance and data output
- Added mass/inertia properties
- Used freeCad for mesh acquisition, Blender for metric refinement, Gazebo model editor for final assembly
- **Note:** Original project was forked by Blender 3D computer graphics software

### Sensor Simulation
- Implemented Hokuyo Fake Laser Scanner in Gazebo
- Implemented Noisy Camera in Gazebo
- Tweaked mean and standard deviation of Gaussian Noise Distribution for higher fidelity outputs

### TurtleBot3 Simulation
- Simulated ROBOTIS waffle-pi/burger TurtleBot3
- Constructed a vehicle in Gazebo using Model Editor
- Loaded with Depth Camera Sensor for surveillance

### Autonomous Navigation (Clearpath Husky)
- Implemented existing functionality of Clearpath Husky Robot:
  - **Mapping:** ROS TF for coordinate frame transforms
  - **Localization:** Adaptive Monte-Carlo Localisation (AMCL) based on particle filter
  - **Global Planning:** A*/Dijkstra algorithms
  - **Local Planning:** Dynamic Window Approach (DWA) / Timed Elastic Band (TEB) local planner
  - Publishes velocity commands to base-controller

---

## Technologies

- ROS (Robot Operating System), ROS TF
- Gazebo, Rviz
- freeCad, Blender, SolidWorks
- AMCL, A*, Dijkstra, DWA, TEB
- Velodyne LiDAR, Hokuyo laser, depth cameras
- URDF, SDF

---

## Resume Appearance

| Resume Version | Included |
|---------------|----------|
| 2020 CV (robotics) | Academic Projects | Yes (detailed, 5+ bullets) |
| 2020 CV (ai) | Academic Projects | Yes (detailed) |
| 2021 robotics | Projects | Yes (condensed) |
| 2022+ | Not included | Dropped |
