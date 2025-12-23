# 10-Element Yagi–Uda Antenna at 38 GHz (CST Simulation)

## Overview
This project implements and validates a **10-element Yagi–Uda antenna operating at 38 GHz** using **CST Studio Suite**.  
The design is based on a published reference paper **[10-Element Yagi Antenna for 38 GHz Frequency](https://ieeexplore.ieee.org/document/10783252)**.

---

## Implementation details
- Antenna configuration: 1 reflector, 1 driven element, 8 directors  
- Geometry and element spacing derived directly from the reference paper  
- All dimensions defined as fractions of the operating wavelength (λ)  
- Material: Perfect Electric Conductor (PEC)  
- Excitation: 50 Ω discrete port at the driven element  
- Simulation tool: CST Studio Suite  

The CST model was constructed using coordinate-based placement to closely match the reference design.

---

## Results and Comparison
The antenna performance was evaluated in terms of return loss, gain, beamwidth, and radiation efficiency.  
The table below compares the **reference paper results** with the **results obtained in this work**.

| Parameter | Reference Paper | This Work |
|---------|----------------|-----------|
| Operating Frequency (GHz) | 38 | 38 |
| Return Loss S11 (dB) | −16.29 | −16.088 |
| Peak Gain (dBi) | 10.88 | 10.8 |
| Half-Power Beamwidth (°) | 51.7 | 52 |
| Radiation Efficiency (%) | 99 | 97.45 |

The close agreement confirms correct implementation and expected end-fire radiation behavior.

---

## Note on CST License
The CST project file in this repository was created using a **student/academic license** of CST Studio Suite.

- Shared strictly for **academic and educational purposes**
- Opening or modifying the `.cst` file requires a valid CST license
- No CST software components are redistributed

---

## Author
[Bhavya Desai](https://github.com/Bhavya-Desaii)
