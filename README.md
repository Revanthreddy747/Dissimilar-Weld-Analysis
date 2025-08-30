# Analysis of Thermal Fields and Residual Stresses in Dissimilar Welded Joints

This repository contains my undergraduate **major project** on the study of **thermal fields** and **residual stresses** developed in **dissimilar welded joints** of **SS316L stainless steel** and **Monel 400**.  

Residual stresses are internal stresses that remain in a material after manufacturing processes like welding. They can significantly affect the **strength, fatigue life, corrosion resistance, and reliability** of welded structures.  
This project investigates how welding parameters influence residual stresses, how they can be measured, and how simulation can help in predicting them.

---

## 📖 Problem Statement
- Welding of dissimilar materials is widely used in **aerospace, marine, nuclear, petrochemical, and power plant applications**.  
- During welding, **non-uniform heating and cooling** causes **thermal gradients**, which lead to **residual stresses**.  
- High residual stresses may cause:
  - Cracking and distortion  
  - Reduced fatigue strength  
  - Poor corrosion resistance  
- Hence, there is a need to **analyze, predict, and control residual stresses** for reliable welded structures.

---

## 🎯 Objectives
1. To weld **SS316L** and **Monel 400** using suitable filler wire (ERNiCrMo-4) and TIG welding process.  
2. To measure residual stresses experimentally using **X-Ray Diffraction (XRD)**.  
3. To analyze **thermal fields** and **stress distribution** using **Finite Element Analysis (FEA) in ANSYS**.  
4. To validate experimental results with numerical simulations.  
5. To determine the **mechanical and metallurgical properties** of the welded joints.  

---

## ⚙️ Methodology

### 🔧 Welding & Material Preparation
- **Base Metals:** SS316L stainless steel and Monel 400  
- **Filler Wire:** ERNiCrMo-4 (Nickel-Chromium-Molybdenum alloy)  
- **Welding Process:** Tungsten Inert Gas (TIG) Welding and Pulsed TIG Welding  
- **Specimen Preparation:**  
  - V-groove butt joints  
  - Cleaned using acetone to remove oxides  
  - EDM cutting for precision samples  

---

### 🔬 Experimental Work
- **Residual Stress Measurement:**  
  - **X-Ray Diffraction (XRD)** method used to determine stresses at weld interface and heat-affected zones.  

- **Mechanical Testing:**  
  - **Tensile Test (ASTM E8 standard)** → yield strength, ultimate tensile strength, ductility  
  - **Hardness Tests:** Brinell and Rockwell methods  
  - **Metallurgical Analysis:** Grain structures, weld pool characteristics  

- **Non-Destructive Testing:**  
  - **Radiography** used to detect weld defects (lack of fusion, porosity, cracks).  

---

### 💻 Numerical Simulation (FEA in ANSYS)
- **Transient Thermal Analysis:**  
  - Heat transfer by **conduction, convection, and radiation** modeled  
  - Applied **moving heat flux** to simulate TIG welding arc  
  - Boundary conditions included arc efficiency, current, and voltage  

- **Structural Analysis:**  
  - Stress distribution obtained from thermal history  
  - Element birth and death technique used for weld bead simulation  
  - Residual stresses and deformations computed  

- **Validation:**  
  - Simulation results compared with experimental XRD measurements  

---

## 📊 Key Results

### ✅ Mechanical Properties
- **Ultimate Tensile Strength (UTS):** ~561 MPa  
- **Yield Strength:** ~225 MPa  
- **Elongation:** ~80%  
- Welded joints showed good mechanical integrity.  

### ✅ Residual Stress (XRD)
- Residual stresses measured at different zones of the weld:  
  - Monel–Monel interface: ~+55 MPa  
  - SS316L–SS316L interface: ~+82 MPa  
  - SS316L–Monel joint: ~216 MPa (highest stresses observed here)  

### ✅ Simulation Results
- ANSYS thermal and structural simulations closely matched experimental data.  
- Thermal fields showed maximum weld temperature of ~1765 °C.  
- Residual stress distribution confirmed the effect of current and voltage on minimizing stresses.  

### ✅ Weld Quality
- Radiography confirmed **defect-free welds**.  
- Hardness values consistent across weld zones.  

---

## 🌍 Impact and Applications
- Demonstrates how **dissimilar materials** (SS316L and Monel 400) can be welded effectively for industrial use.  
- Provides insights into **residual stress control**, improving **fatigue life and corrosion resistance**.  
- Validates how **FEA simulations** can reduce dependency on expensive experimental testing.  
- Useful for industries like:
  - **Marine Engineering** (heat exchangers, pipelines)  
  - **Nuclear Plants** (reactor components)  
  - **Petrochemical Industry** (vessels, tanks)  
  - **Aerospace Applications** (lightweight and high-strength joints)  

---

## 👨‍🔬 Team
- CH. Prashanthi  
- G. Sai Rohit Reddy  
- K. Manisha  
- K. Revanth Reddy  
- P. Hari  

**Supervisor:** Dr. Y. Balram (Associate Professor, Mechanical Engineering, CMRIT)  

---

## 📜 License
This project is licensed under the **MIT License**.
