# Geothermal Heat Exchanger Optimization (Fluidaptic LLC)

This repository documents a project conducted with **Fluidaptic, LLC** to evaluate the **thermal performance and feasibility** of optimized geothermal heat exchangers for use with geothermal heat pumps.  

The project investigates **thermal short-circuiting**, compares **different tube spacings**, and provides **recommendations for improved system efficiency**.

---

## 🌍 Project Background
Conventional geothermal heat exchangers often face challenges with **installation cost** and **thermal interference**.  
This study explores whether optimized designs can achieve **lower installation costs** while maintaining or improving thermal performance.

Key focus:
- Thermal short-circuiting between inlet and outlet loops.  
- Influence of **tube (shank) spacing** on heat transfer.  
- **Simulation-based evaluation** using ANSYS Fluent.  

---

## 🛠️ Methodology
- **Simulation Tool:** ANSYS Fluent (steady-state modeling).  
- **Geometry:** U-tube vertical ground heat exchangers.  
- **Assumptions:**  
  - Steady-state conditions, 100 ft depth.  
  - HDPE tubing (1.315” OD × 1.077” ID).  
  - Water as working fluid (0.142 kg/s).  
  - Minnesota soil thermal properties:contentReference[oaicite:2]{index=2}.  
- **Two Approaches:**  
  1. **Simplified:** Neglect soil, only grout & tubing.  
  2. **Full Model:** Includes grout, soil, and U-tube.  

---

## 📊 Key Results
- **Outlet Temperature:**  
  Largely **independent of tube spacing (2–15 inches)** at steady state.  
- **Approach 1 (Neglect soil):** Nearly identical outlet temps across spacings.  
- **Approach 2 (Include soil):** Similar results, with minor spacing effects.  
- **Outcome:**  
  - **Steady-state:** Tube spacing not critical for final outlet temp.  
  - **Transient/startup:** Spacing may still influence initial performance.  

| Tube Spacing | Inlet Temp (K) | Outlet Temp (K) |
|--------------|---------------|----------------|
| 2”           | 315           | 309.42         |
| 6.5”         | 315           | 309.30         |
| 15”          | 315           | 303.67         |

---

## 💡 Recommendations
1. Use **high-conductivity grout** to reduce thermal short-circuiting.  
2. Optimize **transient behavior** (startup performance) rather than steady state.  
3. Explore **alternative layouts** (multi-U tubes, helical, or borehole-free).  
4. Conduct **cost-performance tradeoff** analysis for deployment feasibility.  

---


---

## 🎯 Deliverables
- **Report:** Comparative thermal performance of geothermal vs. traditional exchangers.  
- **Simulation Results:** Steady-state and transient performance.  
- **Recommendations:** Optimal parameters for integration with existing heat pump systems.  
- **Presentation:** Summary for Fluidaptic LLC’s product development team.  

---

## 📌 Importance
This study supports Fluidaptic LLC in making **data-driven decisions** about future geothermal product development and helps guide **market strategies** for cost-effective, reliable heat exchangers.
