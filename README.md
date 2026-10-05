# Weight Reduction and Optimization of Mars Rover Prototype

A comprehensive engineering study focused on structural analysis, topology optimization, and material substitution to enhance the mechanical efficiency, payload capacity, and mobility of a competitive Mars rover chassis and suspension system.

---

## Project Overview
* **Objective:** Design and optimize a cost-effective, lightweight, and structurally robust rover chassis, suspension, and robotic arm capable of enduring severe off-road constraints for intercollegiate competitions such as the International Rover Challenge (IRC) and European Rover Challenge (ERC).
* **Core Methodologies:** Finite Element Analysis (FEA), multi-component topology optimization, Tsai-Wu composite failure criteria, and material selection trade-off studies.
* **Team & Guidance:** 
  * **Co-Authors:** Ashutosh Mohapatra, Taran Poojari, Mohammed Wafeeq Mohammed Salim Kazi
  * **Faculty Advisor:** Dr. Sachin Mastud (VJTI Mumbai)

---

## Key Technical Workflows & Subsystems

1. **Chassis Optimization:**
   * Evaluated sheet-welded monocoque and space frame configurations.
   * Performed ANSYS structural topology optimization, successfully cutting chassis weight by **30%** (from 6.036 kg to 4.2 kg) while keeping maximum deformation under 0.39 mm.

2. **Rocker-Bogie & Lambda Suspension:**
   * Analyzed passive differential mechanisms and symmetric lambda-bogie linkages to ensure all-wheel ground contact and uniform traction across rough terrain.
   * Optimized suspension links and bogies via iterative FEA, balancing stress distribution and structural compliance.

3. **Robotic Arm & End-Effector:**
   * Modeled a 4-link articulated arm with a 5 kg payload capacity and calculated critical joint torques (46.5 Nm at the shoulder).
   * Conducted material optimization on bevel gears by transitioning from stainless steel to 3D-printed ABS, achieving an **86.7% weight reduction** (180 g down to 24 g) at the end-effector.
   * Performed ANSYS Composite PrepPost (ACP) evaluations on hybrid aluminum-carbon fiber laminates, validating structural safety via the Tsai-Wu failure theory and Inverse Reserve Factors.

---

## Summary of Results

| Subsystem | Initial Weight | Optimized Weight | Performance Gain / Highlight |
| :--- | :--- | :--- | :--- |
| **Rover Chassis** | 6.036 kg | 4.200 kg | **30% mass reduction**; improved stiffness |
| **Differential** | 251.25 g | 195.04 g | Minimized central stress concentration and deflection |
| **Bevel Gears (Arm)** | 180.00 g | 24.00 g | **86.7% reduction** via ABS additive manufacturing |

---

## Documentation & Repository Structure
* **[Download & View Honours Mini Project Report (PDF)](./Mini%20Project.pdf)**: Complete documentation including detailed CAD models, mathematical derivations (Denavit-Hartenberg parameters), ANSYS meshing statistics, and finite element stress contours.
