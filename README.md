# 🌡️ Multi-Effect Evaporator – Process Control Project

### 🎯 Project Overview
This project models and controls a **three-effect evaporator** using **MATLAB/Simulink**.  
It implements nonlinear **mass and energy balance equations** for each effect, and applies a **PID controller** tuned for the final concentration (**C₃**) to maintain product quality.  
The model includes actuator and sensor dynamics, as well as dead time and realistic process disturbances.

---

## ⚙️ Software Requirements
- MATLAB **R2024a** (or newer)
- Simulink Toolbox  
- Control System Toolbox  

---

## 📁 Files Included

| Type | File Name | Description |
|------|------------|-------------|
| MATLAB Script | `setup_evaporator.m` | Initializes all parameters and variables into MATLAB workspace |
| MATLAB Function | `evapmod.m` | Core evaporator dynamic model (mass & energy balance) |
| MATLAB Function | `evapmods.m` | Level-1 S-Function for Simulink (3-effect nonlinear model) |
| MAT File | `control_properties.mat` | Contains tuning parameters and controller constants |
| MAT File | `simulation_properties.mat` | Simulation setup (solver, time, and constants) |
| Simulink Model | `multi_effect_evaporator.slx` | Main model connecting PID, evaporator, and scope |
| PowerPoint | `Process Control Mini-Project.pptx` | Presentation slides for project defense |

---

## ▶️ How to Run the Simulation

1. Open **MATLAB**.  
2. Navigate to your project folder:
   ```matlab
   cd('C:\Users\<YourName>\Desktop\Multi_Effect_Evaporator_Project')
