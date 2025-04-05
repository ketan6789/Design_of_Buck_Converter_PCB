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

![image](https://github.com/user-attachments/assets/837f46f6-1451-4558-b490-a14024229786)




- Created a **3D PCB layout** of the Buck Converter in Proteus.
- The layout includes placement of essential components, tracks, and connectors for future hardware implementation.

### ✔️Simulation of Buck Converter With Gate Driver

![image](https://github.com/user-attachments/assets/ad1eed50-987f-47c3-8664-f5306bd5396c)


- Simulated an **Buck Converter with BJT driver** to drive the MOSFET.
- Helps in understanding switching characteristics and behavior before adding a dedicated gate driver.

## Future Work
- The **TLP250 gate driver** will be used in the physical implementation to drive the MOSFET efficiently.
- Further testing will involve hardware prototyping, PCB printing, and real-world validation of the Buck Converter performance.

## Files Included
- `BuckConverter_ClosedLoop.slx`: Simulink model of the Buck Converter with feedback control.
- `Buckwithdriver.slx`: Proteus simulation of a MOSFET driven using a transistor (BJT).

## Tools Used
- **MATLAB Simulink** for simulation
- **Proteus Design Suite** for schematic and PCB layout
- Planned: **TLP250** for gate driving in hardware

