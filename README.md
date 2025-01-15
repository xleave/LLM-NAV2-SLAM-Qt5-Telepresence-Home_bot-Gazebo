# Telepresence Robot for Memory Impairment Support

## Project Overview
This project focuses on developing a telepresence robot designed to assist individuals with memory impairments. The robot aims to provide memory support functions and facilitate remote interactions through an intuitive interface. The system integrates client applications for interaction and robotic navigation, leveraging advanced technologies to enhance user experience.

---

## Features
1. **Interactive Memory Support System**
   - Activities such as chess games using Pygame.
   - Remote video communication based on open-source platforms.
   - Dialogue with a locally deployed large language model (LLM) via the Ollama API.

2. **Decision-Making Capabilities with LLM**
   - The LLM can process user requests (e.g., "I want to drink water") and autonomously generate JSON commands for the robot to execute tasks.
   - Enables dynamic task allocation and flexible interactions.

3. **Robust Robotic Navigation**
   - ROS 2 Humble for simulation-based navigation.
   - SLAM mapping to generate accurate `.world` environments.
   - Dynamic obstacle detection and avoidance using laser sensors.

4. **User-Friendly Interfaces**
   - A Qt5-based GUI for accessing games, communication, and dialogue features.
   - Potential for map-based robot control directly from the GUI.

---

## Technical Specifications
### Software Stack
- **Programming Languages**: Python, C++ (for ROS 2 components)
- **Frameworks and Tools**: 
  - ROS 2 Humble
  - Qt5 for GUI
  - Pygame for game activities
  - RViz2 and Gazebo for robot simulation
  - Nav2 for navigation and path planning
  - Ollama API using the Llama 3 model for LLM capabilities

### Hardware (Simulation-Based)
- Laser sensors for environment detection.
- Simulated robot models in Gazebo.

### Notable Challenges
- Contextual memory limitations in LLM-based dialogue.
- Fragmentation of functionalities between interaction and navigation systems.
- Manual saving of SLAM-generated maps.

### Acknowledgments
This project incorporates insights and elements from [aimechengineer/HomeBot-ROS2-Navigation](https://github.com/aimechengineer/HomeBot-ROS2-Navigation). Special thanks for the inspiration and foundational work provided.

---

## Future Work
- Integrating physical robot hardware for real-world testing.
- Implementing emotional recognition to enhance interaction quality.
- Automating SLAM map saving and improving the GUI for seamless control.
