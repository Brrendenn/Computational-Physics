# ⚡ Computational Physics Project – Power Electronics Simulation

This project simulates and analyzes the behavior of voltage and current waveforms in a power electronics system. It uses **Python** and relevant libraries to process **CSV-based topology data** and visualize voltage and current patterns for different loads.

---

## 📌 Project Overview

- **Project Topic**: Voltage & Current waveform simulation using power electronics principles.
- **Core Concepts**: Power Electronics, Load Analysis, Computational Modeling.
- **Tools & Technologies**:
  - Python Power Electronics (PPE)
  - CSV file as input topology

---

## 📈 Output Graphs

### 🔋 Voltage Plot Graph
Shows the voltage response for three loads: `vload_1`, `vload_2`, and `vload_3`.  
The voltage signals follow a periodic switching pattern.

### 🔌 Current Plot Graph
Displays the current through each load: `iload_1`, `iload_2`, and `iload_3`.  
The waveform exhibits pulsed characteristics typical of controlled loads.

---

## 🔧 How It Works

1. **Read Topology from CSV**:
   - Loads time series and waveform data from a `.csv` file.

2. **Process with Python**:
   - Cleans and extracts the necessary columns (e.g., time, vload, iload).
   - Uses `pandas` for tabular manipulation and `matplotlib` to visualize results.

3. **Generate Graphs**:
   - Produces two main plots: voltage vs. time and current vs. time.
   - Each load's data is color-coded and labeled.
