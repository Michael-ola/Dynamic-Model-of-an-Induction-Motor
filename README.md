# Dynamic Model of an Induction Motor

## 📌 Project Overview

This project implements the dynamic model of an induction motor using **MATLAB/Simulink**. The simulation analyzes the motor's electrical and mechanical dynamics under different conditions, providing insights into speed, torque, and current characteristics.

## 🎯 Objectives

- Develop and simulate the **mathematical model** of an induction motor.
- Analyze motor performance under **no-load** and **loaded conditions**.
- Visualize motor behavior through **speed, torque, and current waveforms**.

## 🏗️ Methodology

The project is based on fundamental mathematical equations governing induction motor operation. The **Simulink model** includes:

- **Stator and Rotor Voltage Equations**
- **Flux Linkage Equations**
- **Torque Equation**
- **Mechanical Motion Equation**

## ⚙️ Simulink Implementation

The model was built using:

- **Integrator Blocks** (for rotor speed and flux linkage computation)
- **Gain Blocks** (for resistances, inductances, etc.)
- **Sum Blocks** (for algebraic operations)
- **Scope Blocks** (for visualization of results)

## 🔢 Simulation Parameters

| Parameter                 | Value                 |
| ------------------------- | --------------------- |
| Stator Resistance         | 79.13 Ω               |
| Rotor Resistance          | 40.5 Ω                |
| Stator Leakage Inductance | 4.928 - 4.625 H       |
| Mutual Inductance         | 4.625 H               |
| Rotor Leakage Inductance  | 4.928 - 4.625 H       |
| Moment of Inertia         | 0.0038 × 1.5 kg.m²    |
| Viscous Damping           | 0.00071 × 2 N.m.s/rad |
| Supply Voltage            | 310 V                 |
| Pole Pairs                | 4                     |

## 🏁 Simulation Conditions

- **No Load Condition:** The load torque \(T_L\) was set to zero, and the motor ran at rated voltage.
- **Loaded Condition:** A constant load torque was applied to observe its impact on speed and current.

## 🖥️ Results

The following results were obtained from the simulation:

- Simulink Model of the Induction Motor
- Motor Speed at No Load Condition
- Motor Speed with Applied Load Torque
- Electromagnetic Torque vs. Time
- Stator Current Response

## 📌 Conclusion

This project successfully models and simulates an induction motor's dynamic behavior under different operating conditions. MATLAB/Simulink proved to be an effective tool for analyzing induction motor performance, demonstrating variations in speed, torque, and current under different load conditions.

## 📂 Repository Structure

```
📁 Dynamic_Model_of_an_Induction_Motor
 ┣ 🔬 Simulation.slx  # Simulink (.slx) file
 ┣ 🔬 induction_parameter.m # matlab file
 ┣ 📜 README.md       # Project documentation (this file)
```

## 🚀 How to Run the Simulation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Michael-ola/Dynamic-Model-of-an-Induction-Motor.git
   ```
2. **Open MATLAB and navigate to the project folder**
3. **Run the Simulink model:** Open the `.slx` file and click **Run**
4. **View results:** Open the Scope blocks to analyze the waveforms
