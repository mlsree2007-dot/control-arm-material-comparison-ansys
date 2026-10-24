# Comparative Structural, Modal and Fatigue Analysis of a Control Arm Using Cast Al A356-T6 and Structural Steel

## Project Overview

This project presents a comparative finite element analysis of an automotive control arm using Cast Al A356-T6 and Structural Steel under a representative bump load of 40 N using ANSYS Workbench.

The study evaluates the structural, modal and fatigue performance of both materials to determine their suitability for lightweight suspension applications.

---

## Problem Statement

The control arm is a critical suspension component responsible for transmitting loads between the wheel assembly and vehicle chassis. Material selection significantly influences the strength, stiffness, durability, weight and fatigue performance of the component.

This study compares Cast Al A356-T6 and Structural Steel under identical loading and boundary conditions to identify the most suitable material for control arm applications.

---

## Objectives

- Perform structural analysis of the control arm.
- Evaluate equivalent stress and total deformation.
- Perform modal analysis to determine natural frequencies and mode shapes.
- Perform fatigue analysis using the Stress-Life approach.
- Compare the performance of Cast Al A356-T6 and Structural Steel.
- Recommend the most suitable material for control arm applications.

---

## Software Used

- ANSYS Workbench
- ANSYS Mechanical
- SolidWorks (Geometry Preparation)

---

## Material Properties

### Cast Al A356-T6

| Property | Value |
|---|---|
| Density | 2670 kg/m³ |
| Young's Modulus | 72 GPa |
| Yield Strength | 186 MPa |
| Ultimate Strength | 262 MPa |

### Structural Steel

| Property | Value |
|---|---|
| Density | 7850 kg/m³ |
| Young's Modulus | 200 GPa |
| Yield Strength | 250 MPa |
| Ultimate Strength | 460 MPa |

---

## Loading and Boundary Conditions

### Supports

- Fixed support applied at the two mounting bores.

### Load

- Remote force applied at apex hole.
- Magnitude: 40 N
- Direction: Negative Y-axis
- Behavior: Deformable

---

## Mesh Details

| Parameter | Value |
|---|---|
| Element Type | Quadratic Tetrahedral |
| Global Mesh Size | 1.5 mm |
| Face Sizing | 0.3 mm |
| Nodes | 115,696 |

---

## Mesh Convergence Study

| Mesh | Nodes | Max Stress (MPa) |
|---|---|---|
| Mesh 1 | 55,165 | 28.04 |
| Mesh 2 | 74,599 | 32.71 |
| Mesh 3 | 115,696 | 32.16 |

### Convergence Check

**% Change**

= (32.16 − 32.71) / 32.16 × 100

= 1.71%

Since the variation is less than 5%, Mesh 3 was selected for all analyses.

---

## Structural Analysis Results

| Result | Cast Al A356-T6 | Structural Steel |
|---|---|---|
| Maximum Stress | 32.21 MPa | 32.16 MPa |
| Maximum Deformation | 0.0488 mm | 0.0176 mm |
| Safety Factor | 5.77 | 7.77 |

### Observation

Structural Steel exhibited lower deformation and a higher safety factor because of its greater stiffness.

---

## Modal Analysis Results

| Mode | A356-T6 (Hz) | Structural Steel (Hz) |
|---|---|---|
| Mode 1 | 2927 | 2842 |
| Mode 2 | 12662 | 12267 |
| Mode 3 | 12725 | 12585 |
| Mode 4 | 14666 | 14242 |
| Mode 5 | 24136 | 23394 |
| Mode 6 | 26004 | 25194 |

### Observation

Cast Al A356-T6 exhibited slightly higher natural frequencies because of its higher stiffness-to-density ratio.

---

## Fatigue Analysis Results

| Result | Cast Al A356-T6 | Structural Steel |
|---|---|---|
| Design Life | 5×10⁶ cycles | 10⁶ cycles |
| Life | 5×10⁶ cycles | 10⁶ cycles |
| Damage | 1 | 1 |
| Fatigue Safety Factor | 4.16 | 4.52 |

### Observation

Both materials satisfied the fatigue requirements with safety factors greater than 1.

---

## Conclusion

- Both materials successfully passed structural, modal and fatigue analyses.
- Structural Steel exhibited lower deformation and higher safety factors.
- Cast Al A356-T6 provided higher natural frequencies and significant weight reduction.
- Cast Al A356-T6 can be considered a lightweight alternative to Structural Steel for control arm applications.

---

## Author

LATHIKKA SREE M

Department of Biomedical Engineering

2026
