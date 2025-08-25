# DAMHS – Automatisiertes Materialhandlingsystem

<p align="left">
  <img src="https://img.shields.io/badge/Focus-Automation-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Methods-Simulation%20%7C%20Layout%20Design%20%7C%20Sensors-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-brightgreen?style=for-the-badge" />
</p>

Design & evaluation of an automated material handling system: conveyors, diverters, buffer logic, sensors/cameras, 
and performance analysis (throughput, utilization, reliability).

---

## ⭐ STAR Summary
- **Situation:** The post-processing line required an automated handling solution to reach ~**90 bars/hour** while avoiding 100% utilization at bottlenecks.
- **Task:** Select components (conveyors/diverters/sensors), develop alternative layouts, and quantify throughput, utilization, and buffers.
- **Action:** Built/evaluated multiple layouts; computed machine counts & waiting elements; positioned sensors & vision checks; compared reliability and power/length estimates.
- **Result:** **Target throughput achieved** via optimized layout and buffer sizing; improved reliability by keeping critical stations below full utilization.

---

## 🖼️ Highlights
![Final Layout](docs/figures/layout-final.png)
![Utilization Table](docs/figures/utilization-table.png)

---

## 📂 Repository Map
- `docs/reports/` – sanitized PDF
- `docs/figures/` – layout and KPI charts
- `docs/artifacts/` – throughput/utilization CSVs
- `src/` – (optional) small calculators/scripts
- `LICENSE` – MIT
