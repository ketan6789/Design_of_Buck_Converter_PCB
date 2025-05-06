[![View Design_of_Buck_Converter_PCB on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://in.mathworks.com/matlabcentral/fileexchange/180669-design_of_buck_converter_pcb)
# Buck Converter Design and Simulation



## Overview
This project focuses on the **design and simulation of a 50V Buck Converter**, primarily aimed at efficient DC-DC voltage regulation. The project is currently in its simulation and design phase and demonstrates a complete closed-loop control simulation using MATLAB Simulink, as well as 3D PCB layout design using Proteus.

## Current Progress

### ✔️ Closed-Loop Buck Converter Simulation (Simulink)

![image](https://github.com/user-attachments/assets/9f35c5ce-f898-4343-8723-3f62775d9692)


- Designed and simulated a **closed-loop Buck Converter** using MATLAB Simulink.
- The system regulates the output voltage with feedback, ensuring stable operation under varying load conditions.
- Core components modeled include:
  - MOSFET as the main switching device
  - Inductor, capacitor, and load resistor setup
  - PWM generation and control logic

### ✔️ Proteus PCB Design

![Screenshot 2025-05-01 013137](https://github.com/user-attachments/assets/6d87e37a-0dc7-4fa7-92fb-bbd85b5b4254)
- PCB layout 

![Screenshot 2025-04-30 204402](https://github.com/user-attachments/assets/48b6c55a-1017-45f4-baf5-330a286c8467)

- Created a **3D PCB layout** of the Buck Converter in Proteus.
- The layout includes placement of essential components, tracks, and connectors for future hardware implementation.

### ✔️Simulation of Buck Converter With Gate Driver

![image](https://github.com/user-attachments/assets/ad1eed50-987f-47c3-8664-f5306bd5396c)

- Simulated an **Buck Converter with BJT driver** to drive the MOSFET.
- Helps in understanding switching characteristics and behavior before adding a dedicated gate driver.

## Hardware Implementation

<img src="https://github.com/user-attachments/assets/18bc2709-08c4-4ebd-9575-a645904c3272" width="600" height="400"/>

- BUCK Converter Setup on Breadboard
  
<img src="https://github.com/user-attachments/assets/b385ec43-aa9f-4d42-873b-8f79ae9d5c85" width="600" height="700"/>

- Complete Setup of Buck Converter
- Note the output is a square wave as the LC filter was disconnected.


## Files Included
- `BuckConverter_ClosedLoop.slx`: Simulink model of the Buck Converter with feedback control.
- `Buckwithdriver.slx`: Proteus simulation of a MOSFET driven using a transistor (BJT).

## Tools Used
- **MATLAB Simulink** for simulation
- **Proteus Design Suite** for schematic and PCB layout
- Planned: **TLP250** for gate driving in hardware

