# 🌉 Design of Steel Structures (IS 800:2007)

# DESIGN METHODOLOGIES

## 1. Working Stress Method (WSM)

### Concept
Also known as the **Elastic Design Method** or **Allowable Stress Design**, the structure is designed so that stresses under working loads do not exceed a permissible or allowable stress. This allowable stress is derived by dividing the material's yield stress by a **factor of safety**.

### Design Principle
```
σ_actual ≤ σ_allowable = f_y / Factor of Safety
```
- Loads considered are **service loads** (actual expected loads).
- Material is assumed to behave **elastically**.

### Advantages
- **Simple** and straightforward calculations.
- Long history of use, well-understood.
- **Conservative** due to a single global factor of safety.

### Disadvantages
- **Uneconomical** – does not account for reserve strength beyond yield.
- Single factor of safety does not differentiate between load types or material uncertainties.
- Does not explicitly consider ultimate capacity or failure modes.

### Uses Today
- Design of **auxiliary elements** and temporary structures.
- Some **retrofit assessments** and older code-based projects.
- **Educational** tool for basic concepts.

### Relevant IS Code
- **IS 800:1984** – *Code of Practice for General Construction in Steel* (Superseded).

---

## 2. Limit State Method (LSM)

### Concept
A **probabilistic, performance-based** approach. The structure is designed to satisfy:
1.  **Limit State of Strength** (Safety against collapse)
2.  **Limit State of Serviceability** (Deflection, vibration, etc.)

It uses **partial safety factors** applied separately to loads and material strength.

### Design Principle
**For Strength Limit State:**
```
Design Action (Factored Load) ≤ Design Resistance
```
- **Load factors** (γ_f) are applied to different load types.
- **Material resistance factor** (γ_m) is applied to material strength.

**For Serviceability Limit State:**
- Checks are performed under **service loads**.

### Advantages
- **Economical** – utilizes material strength more efficiently.
- **Rational** – accounts for variability in loads and materials separately.
- **Comprehensive** – considers both strength and serviceability.

### Disadvantages
- **More complex** calculations.
- Requires understanding of partial safety factors and multiple limit states.

### Uses Today
- **Mandatory** for all major steel structures per current Indian codes.
- Used in **buildings, bridges, industrial structures**.
- Basis for **international codes** (Eurocode, AISC LRFD).

### Relevant IS Code
- **IS 800:2007** – *General Construction in Steel – Code of Practice* (Current Standard).

---

## 3. Key Differences Between WSM and LSM

| **Aspect**                | **Working Stress Method (WSM)**                          | **Limit State Method (LSM)**                               |
|---------------------------|----------------------------------------------------------|------------------------------------------------------------|
| **Philosophy**            | Stress-based; linear elastic                             | State-based; considers ultimate & serviceability states    |
| **Safety Approach**       | Single factor of safety on yield stress                  | Partial safety factors on loads and materials              |
| **Load Considered**       | Service loads (unfactored)                               | Factored loads (using load combinations)                   |
| **Material Strength**     | Allowable stress = f_y / FOS                             | Design strength = f_y / γ_m                                |
| **Economy**               | Generally uneconomical                                   | More economical                                            |
| **Complexity**            | Simpler                                                  | More complex                                               |
| **Governing IS Code**     | IS 800:1984                                              | IS 800:2007                                                |
| **Design Focus**          | Stress at working load                                   | Collapse prevention and usability under service conditions |

---

## 4. Summary

The **Working Stress Method** is a traditional, conservative approach focusing on elastic behavior under service loads. The **Limit State Method** is a modern, rational method that designs against collapse and ensures performance, leading to more economical and reliable structures.

**IS 800:2007** fully adopts the Limit State Method as the standard for new steel designs in India, while WSM (IS 800:1984) is primarily of historical or educational relevance.

> **Note:** For all practical and new designs, engineers must follow the latest codal provisions—**IS 800:2007 (Limit State Method)**.
