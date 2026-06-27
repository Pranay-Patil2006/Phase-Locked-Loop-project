# Phase-Locked-Loop Project

**This Project was part of EE322: Analog and Mixed Signal Circuits Course**
**Design and implementation on PCB of a phase-locked loop**

---

## Summary
Designed, simulated, and validated a discrete analog Phase-Locked Loop (PLL) implemented on PCB using a CD4046 phase detector, discrete op-amps, and passive/active loop-filter components. The design was optimized to minimize phase jitter and maximize capture and lock range, with close agreement between simulation and hardware measurements.

---

## Key Contributions
- **Loop design & analysis:** Derived loop-filter values from the closed-loop transfer function; verified lock time and stability margins using time-domain analysis.
- **Simulation strategy:** Performed LTSpice transient simulations and parameter sweeps to evaluate capture range, locking behavior, and sensitivity to component variations.
- **Jitter reduction tactics:** Reduced jitter through optimized loop bandwidth selection, low-noise op-amp choice, VCO linearization, proper supply decoupling, and careful PCB routing of phase detector and VCO control nodes.
- **Validation:** Conducted testbench measurements of lock acquisition and short-term phase stability to confirm simulation trends and guide final component tuning.

---

## Block Diagram
![Simple block diagram of the circuit](https://github.com/user-attachments/assets/5bbacfaf-0d9f-4a72-a4d4-9f07debf6e73)

*Credits: https://electronicscoach.com/phase-locked-loops.html*

---

## Results
- **Measured capture/lock range:** 150Hz - 1300Hz 
