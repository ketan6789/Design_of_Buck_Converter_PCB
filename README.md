# Buck Converter Design and Simulation

## Overview
This project focuses on the **design and simulation of a 30V Buck Converter**, aimed at efficient DC-DC voltage regulation. It involves both closed-loop simulation in MATLAB Simulink and practical implementation on hardware using a TLP250 gate driver. A Proteus-based PCB layout was also developed. The project provided deep insights into gate driving, switching behavior, and practical challenges in real-world converter applications.

## Current Progress

### ✔️ Closed-Loop Buck Converter Simulation (Simulink)
![image](https://github.com/user-attachments/assets/9f35c5ce-f898-4343-8723-3f62775d9692)

- Designed and simulated a **closed-loop Buck Converter** using MATLAB Simulink.
- Regulates output voltage with feedback to maintain stability under varying loads.
- Components modeled:
  - MOSFET as the switching device
  - Inductor, capacitor, and resistive load
  - PWM generation and control

### ✔️ Proteus PCB Design
![Screenshot 2025-05-01 013137](https://github.com/user-attachments/assets/6d87e37a-0dc7-4fa7-92fb-bbd85b5b4254)

- PCB layout 

![Screenshot 2025-04-30 204402](https://github.com/user-attachments/assets/48b6c55a-1017-45f4-baf5-330a286c8467)

- Developed a **3D PCB layout** of the Buck Converter in Proteus.
- Includes component placement, tracks, and terminals.
- Due to unsatisfactory hardware results, the PCB was not fabricated.

### ✔️ Simulation of Buck Converter With Gate Driver
![image](https://github.com/user-attachments/assets/ad1eed50-987f-47c3-8664-f5306bd5396c)

- Simulated Buck Converter with a **BJT-based gate driver**.
- Helped understand switching behavior and power control dynamics.

## ✔️ Hardware Implementation and Testing

<img src="https://github.com/user-attachments/assets/18bc2709-08c4-4ebd-9575-a645904c3272" width="600" height="400"/>

- Assembled and tested **TLP250-based gate driver** circuit.
- Verified operation through LED blinking and basic switching of an IGBT.

<img src="https://github.com/user-attachments/assets/b385ec43-aa9f-4d42-873b-8f79ae9d5c85" width="600" height="700"/>

- Integrated TLP250 gate driver into Buck Converter setup.
- Initial tests at 0.5 duty cycle showed partial success (e.g., 10–11V output from 20V input).
- Output at other duty cycles was inconsistent and did not match expected theoretical values.
- The LC filter improved performance but didn't fully resolve voltage errors.

## Final Note

Although full expected performance was not achieved, this project offered hands-on experience in **power electronics hardware**, **PWM control**, **gate driving**, and **DC-DC converter design**. It also highlighted the importance of component selection, noise considerations, and real-world non-idealities.

---

## Files Included
- `BuckConverter_ClosedLoop.slx`: Simulink model of the Buck Converter with feedback control.
- `Buckwithdriver.slx`: Simulation of a transistor-based gate driver circuit.

## Tools Used
- **MATLAB Simulink**
- **Proteus Design Suite**
- **Hardware Testing with TLP250 Gate Driver**
