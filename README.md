# README: Design and Simulation of Resonant Inductive Coupling Wireless Power Transfer System for Electric Vehicles Applications

## Overview
This project explores the design, simulation, and analysis of a 5KW Resonant Inductive Wireless Power Transfer (WPT) system for Electric Vehicles (EVs). It integrates EVs with Medium Voltage DC (MVDC) networks, leveraging resonant circuit topologies to enhance the performance and efficiency of wireless inductive power transfer (IPT) systems.

## Objectives
- Design and analyze a WPT system using resonant inductive coupling.
- Integrate the WPT system with MVDC networks for improved system performance.
- Develop simulation models and validate results through hardware testing.
- Address the limitations of existing IPT systems using resonant circuits.

## Key Features
1. **Wireless Power Transfer (WPT):**  
   - Inductive Power Transfer (IPT) for near-field energy transmission.
   - Resonant circuits to enhance efficiency and power delivery.

2. **Medium Voltage DC (MVDC) Networks:**  
   - Integration with MVDC to reduce energy losses.
   - Simplification of power conversion stages in EV charging.

3. **Simulation and Hardware Implementation:**  
   - Simulation of circuit designs for performance evaluation.
   - Hardware testing to validate simulation results.

4. **Environmentally Friendly:**  
   - Reduced carbon footprint compared to traditional charging methods.
   - Robust and reliable system design for real-world applications.

## Advantages
- Reduced dependency on fossil fuels.
- High efficiency and low maintenance.
- Minimal impact on human health and the environment.

## Limitations Addressed
- Enhanced performance over long distances using resonant circuits.
- Mitigated efficiency loss due to coil misalignment.
- Overcoming challenges associated with traditional IPT systems.

## System Components
1. **Power Conversion Stages:**
   - AC to DC rectifier.
   - High-frequency inverter for resonant circuits.

2. **Resonant Circuits:**
   - Optimized for maximum performance at resonance frequency.

3. **Wireless Power Transmission:**
   - Transmitter and receiver coils based on mutual inductance.

## Structure of the Thesis
### Chapter 1: Introduction
- Overview of EVs, MVDC networks, and WPT technologies.
- Challenges and advantages of integrating IPT with MVDC systems.

### Chapter 2: Resonant Inductive Power Transfer
- Design approach for a 5KW WPT system.
- Description of circuit components and their roles.

### Chapter 3: Simulation Analysis
- Circuit model simulations and theoretical calculations.
- Performance analysis of simulated results.

### Chapter 4: Hardware Implementation
- Testing and validation of the proposed system.
- Comparison of simulation and hardware test results.

### Chapter 5: Conclusion
- Summary of findings and recommendations for practical applications.

## Getting Started
1. Clone this repository.
   ```bash
   git clone https://github.com/username/resonant-ipt-ev
   ```

2. Install dependencies:
   - MATLAB/Simulink for simulation.
   - Required hardware components for testing.

3. Run the simulations in MATLAB/Simulink to validate the design.

4. Implement the hardware setup and compare results with simulations.

## Requirements
- **Software:** MATLAB/Simulink.
- **Hardware:**
  - Transmitter and receiver coils.
  - Rectifier and inverter components.
  - Resonant circuit elements (capacitors, inductors).

## Results
# Simulation Test Results for Hardware Specifications

## Overview of the Simulation System

![5 3](https://github.com/user-attachments/assets/98e3fd6b-d7ce-42d5-b629-1ece82c04531)

The simulation system implementation for a low-power circuit is depicted in Fig 25.

![5 3](https://github.com/user-attachments/assets/f6f9d216-dc59-4f94-ba0f-9d374e560674)

**Fig 25**: Simulation system for low-power circuit

The simulation output waveforms for the implemented hardware model are presented in the following figures:

- **Output of Inverter**
- 
![5 3](https://github.com/user-attachments/assets/45a956c8-0e50-43dd-aeb3-66043e8b2945)

  **Fig 26**: Inverter simulation result of low-power circuit

- **Capacitor Voltage**
- 
![5 3](https://github.com/user-attachments/assets/f83a44d5-e1e9-4372-a823-8d8da8f8ef44)

  **Fig 27**: Simulation result of voltage across Capacitor for low-power circuit

- **Inductor Voltage**

![5 3](https://github.com/user-attachments/assets/4db76ae3-6a65-4111-81ac-e936720961cc)

  **Fig 28**: Simulation result of voltage across Inductor for low-power circuit

- **Input Current**

![5 3](https://github.com/user-attachments/assets/574ed299-cda6-410e-947f-2ea171164c35)

  **Fig 29**: Simulation result of Input Current for low-power circuit

- **Inductor Current**

![5 3](https://github.com/user-attachments/assets/39c03b18-8d79-4a7e-b7c8-3429ee73549f)

  **Fig 30**: Simulation result of Inductor Current for low-power circuit

- **Output Voltage across Secondary Winding**

![5 3](https://github.com/user-attachments/assets/db6774a8-2b18-439f-b39d-53ee0cc7e10c)

  **Fig 31**: Simulation result of output voltage across secondary winding for low-power circuit

## Observations and Analysis

The simulation results are observed to be closely aligned with theoretical calculations. Table 15 compares the theoretical calculations with the simulation results for the low-power test bed specifications.

### Table 15. Comparison of Calculated Values and Simulation Results for Low-Power Test Bed

| Parameter                   | Theoretically Calculated Value   | Value Obtained from Simulation |
|-----------------------------|-----------------------------------|---------------------------------|
| Voltage across Inductor     | 61.188 V (rms), 86.53 V (peak)   | 87.5 V (peak)                  |
| Voltage across Capacitor    | 60 V (rms), 84.85 V (peak)       | 77.1 V (peak)                  |
| Input Current               | 0.5226 A (rms), 0.739 A (peak)   | 0.704 A (peak)                 |
| Current through Inductor    | 0.512 A (rms), 0.724 A (peak)    | 0.643 A (peak)                 |
| Output Voltage on Secondary | 24.475 V (rms), 34.613 V (peak)  | 34.44 V (peak)                 |

## Conclusion

From the above results, we can conclude that the theoretical calculations are verified by the simulation results for the low-power test bed.

## License
This project is licensed under the [MIT License](LICENSE).
