
# P01 — Pressure Vessel Nozzle Structural Analysis

![Software](https://img.shields.io/badge/Software-ANSYS_APDL-orange)
![Analysis](https://img.shields.io/badge/Analysis-Static_Structural-blue)
![Status](https://img.shields.io/badge/Status-In_Progress-yellow)

## 1. Project Overview

This project investigates the structural integrity and
stress concentration of a cylindrical pressure vessel
with a radial nozzle under internal pressure using
the finite element method (FEM).

## 2. Project Objectives

- Develop a three-dimensional finite element model.
- Investigate nozzle-to-shell stress concentration.
- Evaluate von Mises and principal stresses.
- Determine structural deformation.
- Perform a mesh convergence study.
- Compare numerical and analytical results.
- Investigate potential design improvements.

## 3. Software

- ANSYS Mechanical APDL Classic
- Python for data analysis and visualization
- Microsoft Excel for engineering calculations

## 4. Geometry Specifications

| Parameter | Value |
|---|---:|
| Vessel length | 2000 mm |
| Vessel internal diameter | 1000 mm |
| Vessel external diameter | 1020 mm |
| Vessel wall thickness | 10 mm |
| Nozzle internal diameter | 200 mm |
| Nozzle external diameter | 220 mm |
| Nozzle wall thickness | 10 mm |
| Nozzle projection | 300 mm |
| Nozzle axial position | 1000 mm |
| Nozzle orientation | 90 degrees |

## 5. Material Properties

Material: Representative P265GH Steel

| Property | Value |
|---|---:|
| Young's modulus | 210000 MPa |
| Poisson's ratio | 0.30 |
| Density | 7850 kg/m³ |
| Reference yield strength | 265 MPa |

Material properties are preliminary educational
assumptions and require verification.

## 6. Loading Conditions

- Internal pressure: 1 MPa (10 bar)
- External gauge pressure: 0 MPa
- Equivalent closed-end pressure loads
- Boundary conditions to be verified

## 7. Finite Element Methodology

- Element type: SOLID186
- Three-dimensional structural analysis
- Linear elastic material model
- Local mesh refinement at nozzle junction
- Mesh convergence investigation

## 8. Engineering Standards

Reference framework:

- DIN EN 13445
- Pressure vessel engineering principles

Formal code compliance has not yet been established.

## 9. Project Progress

- [x] Project definition
- [x] Geometry specifications
- [x] Preliminary material selection
- [ ] Geometry creation
- [ ] Mesh generation
- [ ] Boundary conditions
- [ ] Solver configuration
- [ ] Stress analysis
- [ ] Deformation analysis
- [ ] Mesh convergence
- [ ] Analytical verification
- [ ] Design optimization
- [ ] Final technical report

## 10. Simulation Results

Results will be uploaded after completing
and verifying the finite element analysis.

## 11. Verification and Validation

Pending completion of numerical simulations
and analytical calculations.

## 12. Conclusion

To be completed after the simulation study.

---

Author: Abdul Samad

Hochschule Stralsund, Germany

Master's in Simulation and System Design
