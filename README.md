# Minor-Project-Logitech-G29-in-Virtual-Driving-Simulations

## 📌 Project Overview  
This project explores the **integration of the Logitech G29 steering wheel controller with the CARLA simulator** to enhance the realism of virtual driving simulations. CARLA is an open-source simulator widely used for **autonomous vehicle research**, and integrating the Logitech G29 allows for **manual control, human-in-the-loop testing, and realistic driving data collection**.  

## 🚀 Key Features  
- 🎮 **Steering, Acceleration & Braking Mapping** – Configured Logitech G29 inputs for manual control in CARLA.  
- ⚙️ **Force Feedback & Responsiveness** – Evaluated input latency, force feedback realism, and response time.  
- 🏎️ **Autonomous Path Planning** – Utilized the **A* Algorithm** for optimized pathfinding and recorded steering angle data.  
- 🚦 **Traffic Signal & Obstacle Handling** – Stopped at red lights and avoided static obstacles with smooth turns.  
- 🔄 **Human-In-The-Loop Testing** – Integrated manual driving with autonomous algorithms for data collection.  

## 📑 System Design  
### 🔹 Block Diagram with Logitech G29  
- **Interfacing Logitech G29 with CARLA using jstest-gtk and Pygame**  
- **Mapping Controller Inputs for Accurate Steering, Throttle & Braking**  
- **Testing Responsiveness & Performance Metrics in Virtual Driving Scenarios**  
- **Validating Controller Integration for Autonomous Driving Research**  

### 🔹 A* Algorithm Implementation  
The **A* Algorithm** was used to compute the **shortest and most efficient path** while maintaining smooth lane shifts when obstacles were detected.  
Formula:  
```math
f(n) = g(n) + h(n)
```
Where:

-  g(n) → Cost to reach the current node
-  h(n) → Heuristic estimate to the goal


📌 *Waypoint-based path planning was implemented to ensure smooth navigation.*  

## 🛠️ Implementation Details  
- **Programming Language:** Python  
- **Simulator:** [CARLA](https://carla.org/)  
- **Path Planning Algorithm:** A* Algorithm  
- **Input Mapping Tool:** jstest-gtk, Pygame  
- **Hardware:** Logitech G29 Steering Wheel & Pedals  

## 📊 Results & Observations  
- ✅ **Logitech G29 successfully mapped for manual driving in CARLA.**  
- ✅ **Smooth and realistic force feedback enhances the driving experience.**  
- ✅ **Autonomous path planning (A* Algorithm) effectively navigates CARLA environments.**  
- ✅ **Traffic signal handling & obstacle avoidance function correctly.**  

## 🔮 Future Scope  
- 🚀 **Enhancing Realism:** Improve force feedback models and real-world physics simulation.  
- 🔄 **Dynamic Path Planning:** Implement real-time avoidance for moving obstacles and traffic.  
- 🧠 **Machine Learning Integration:** Train AI models using collected human driving data.  
- 🎮 **Multi-Device Support:** Expand support for other steering wheel controllers.  
