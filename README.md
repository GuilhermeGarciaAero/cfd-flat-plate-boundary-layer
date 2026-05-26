# cfd-flat-plate-boundary-layer
# 🌊 CFD Simulation — Flat Plate Boundary Layer

Numerical simulation of laminar/turbulent boundary layer development
over a flat plate using ANSYS Fluent 2021 R2.

---

## 📌 Overview

This project simulates the external flow over a flat plate to analyze
boundary layer growth, velocity profiles, and wall shear stress
distribution. The study validates numerical results against the
classical Blasius solution for laminar flow.

---

## 🗂️ Domain Setup
| Boundary     | Condition         |
|--------------|-------------------|
| Inlet        | Velocity Inlet    |
| Outlet       | Pressure Outlet   |
| Top (Far)    | Symmetry          |
| Flat Plate   | No-slip Wall      |

---

## ⚙️ Simulation Parameters

| Parameter         | Value              |
|-------------------|--------------------|
| Software          | ANSYS Fluent 2021 R2 |
| Flow Type         | External / Incompressible |
| Fluid             | Air (standard conditions) |
| Inlet Velocity    |  1 m/s   |

---

## 🧱 Mesh

- Structured mesh with boundary layer refinement near the wall
- First cell height defined by y⁺ target
- Mesh independence study performed

> 📷 *Mesh and results images coming soon*

---

## 📊 Results

- [x] Velocity contours
- [x] Boundary layer thickness along the plate
- [x] Velocity profile comparison with Blasius solution
- [x] Wall shear stress distribution

---

## 🛠️ Tools Used

![ANSYS](https://img.shields.io/badge/ANSYS-Fluent_2021_R2-yellow?style=flat)
![CFD](https://img.shields.io/badge/CFD-Simulation-blue?style=flat)
![MATLAB](https://img.shields.io/badge/MATLAB-Post--processing-orange?style=flat)

---

## 👨‍💻 Author

**Guilherme Garcia**  
Aerospace Engineer — UnB (2024)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Guilherme_Garcia-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/guilherme-garcia-guedes-aeroespacial/)
