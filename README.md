# numpy-ev-performance-study
"A comprehensive, multi-phase engineering study of the 2025 EV market. Leverages high-performance NumPy computing for vectorized data processing, battery degradation modeling, range optimization benchmarks, and statistical multidimensional analysis."

# ⚡ 2025 EV Market Analysis
> An end-to-end data study of Electric Vehicle performance and battery engineering.

## 📊 Phase 1: Numerical Benchmarking
**Status:** Completed ✅ | **Core Tools:** NumPy, Pandas

### 📝 Overview
In this initial phase, I focused on high-performance data processing using **vectorized operations**. By converting the 2025 EV dataset into NumPy arrays, I bypassed standard iterative loops to perform rapid statistical filtering and market benchmarking.

*Note: The complete codebase and datasets will be released following the completion of all 6 phases.*

### 🔍 Key Analysis
* **The 400km Standard:** Identified a major market cluster of **229 vehicles** that successfully pair a >70kWh battery with a >400km range, marking the new industry benchmark for consumer EVs.
* **Range Performance:** Analysis confirmed the **Mercedes EQS 450+** as the current range leader (**685 km**), while city-optimized models like the **Fiat 500e** define the lower bound at **135 km**.
* **Engineering Efficiency:** The **Dacia Spring Electric 45** was identified as the most efficient model (**109 Wh/km**), highlighting the impact of weight-to-power optimization.
* **Battery Correlation:** Statistical mean analysis shows that vehicles with 70kWh+ batteries achieve an average range of **461 km**, proving a strong linear scaling between capacity and utility.
---

## 🛠️ Project Workflow & Data
This repository follows a structured data engineering workflow to analyze the 2025 EV market.

1. **Data Ingestion:** Technical specs for 2025 models are stored in [`data/electric_vehicles_spec_2025.csv`](./data/electric_vehicles_spec_2025.csv).
2. **Documentation:** A comprehensive [Data Dictionary](./DATA_DICTIONARY.md) defines the 22 variables used, including SI units and battery chemistry.
3. **Analysis:** The raw data is processed using NumPy for vectorized performance benchmarking, focusing on energy efficiency (Wh/km) and torque-to-weight ratios.

**Author:** [Kartik Thakkar](https://github.com/Kartikthakkarr)
