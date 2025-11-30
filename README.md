
# Automated Tank Filling System 🚰

## Project Overview
This project simulates an automated water tank level control system. It utilizes PID logic  to maintain water levels between specific setpoints, discharging automatically when the threshold is reached.

## 🛠 Tools Used
* **Logic:** Siemens TIA Portal V15.1 (Ladder Diagram)
* **Simulation:** Factory I/O
* **HMI:** Siemens TP1500 Comfort Pro (Simulated)

## ⚙️ How it Works
1.  **System Start:** Checks if the tank is empty (0cm).
2.  **Filling Phase:** Fill Valve opens until the Level Sensor detects 250cm.
3.  **Discharge Phase:** Once 250cm is reached, the Fill Valve closes and the Discharge Valve opens.
4.  **Reset:** Discharge continues until the level drops to 100cm, triggering the cycle to restart.

## 📂 Files Included
* `.zap17`: Complete TIA Portal Project Archive.
* `.fio`: Factory I/O Scene file.

## 🎥 Demo
(https://www.linkedin.com/posts/ahmmvd_automation-siemens-tiaportal-activity-7400852670732808192-9ft8?utm_source=share&utm_medium=member_desktop&rcm=ACoAADk01YQBjfC-WgStnXbhIyrJOVlpMkgdL1Q)
