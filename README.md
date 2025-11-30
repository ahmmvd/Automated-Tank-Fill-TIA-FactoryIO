
# Automated Tank Filling System 🚰

## Project Overview
This project simulates an automated water tank level control system. It utilizes PID logic  to maintain water levels between specific setpoints, discharging automatically when the threshold is reached.

## 🛠 Tools Used
* **Logic:** Siemens TIA Portal V17 (Ladder Diagram)
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
[Link to your LinkedIn Video post can go here later]
