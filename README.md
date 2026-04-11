📦 Project Phases:
Phase 1 → Numerical Benchmarking ✅  
Phase 2 → Derived Metrics & Performance Analysis ✅


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

   📊 Phase 2: EV Performance Analysis with Derived Metrics

Status: Completed ✅ | Core Tools: NumPy, Pandas

📝 Overview

Building upon the numerical benchmarking foundation established in Phase 1, this phase introduces engineering-grade derived metrics to transform raw EV specifications into meaningful performance indicators.

The focus shifts from descriptive analysis to quantitative modeling, enabling a deeper evaluation of electric vehicles across efficiency, power delivery, and real-world usability.

By leveraging NumPy’s vectorized computation capabilities, large-scale metric calculations and rankings were executed with high efficiency and consistency.

⚙️ Methodology
🔹 Efficiency Score (Energy Utilization Model)

A normalized metric designed to evaluate how effectively a vehicle converts battery capacity into usable range.

Based on: Range (km) / Battery Capacity (kWh)
Interpreted as: km per kWh
Purpose: Identify vehicles with superior energy optimization and minimal losses
🔹 Performance Score (Composite Engineering Index)

A multi-variable scoring model combining key performance indicators:

Range (endurance capability)
Torque (power delivery)
Acceleration (responsiveness)

This composite index enables holistic vehicle ranking, balancing efficiency with performance dynamics.

🔹 Vectorized Ranking & Filtering

All computations were executed using NumPy vectorization, eliminating iterative loops and enabling:

Rapid multi-dimensional sorting
Conditional filtering (e.g., range > 400 km)
Scalable performance benchmarking across the dataset
🔍 Key Analysis
⚡ Performance Leaders

Identified top-performing EVs based on the composite Performance Score, highlighting models that achieve an optimal balance between range, torque, and acceleration.

🔋 Efficiency Extremes
Determined the highest efficiency vehicle in the dataset
Identified the second-best performer, validating consistency in efficiency trends

These findings emphasize the role of lightweight design and powertrain optimization in maximizing energy utilization.

🚗 400km+ Segment Deep Dive

Focused analysis on EVs exceeding the 400 km benchmark, evaluating:

Performance score distribution
Efficiency consistency across high-range vehicles
Engineering trade-offs in premium EV segments
🏆 Benchmark Rankings
Extracted Top 5 vehicles (range-based)
Extracted Top 10 vehicles (performance-based)

These rankings provide a clear, data-driven snapshot of market leaders in 2025 EV engineering.

📈 Outcome

Phase 2 significantly elevates the analytical depth of the project by introducing custom performance modeling frameworks.

It moves beyond raw data interpretation and establishes a structured evaluation system, enabling:

Objective EV comparison
Scalable ranking methodologies
Insight-driven engineering conclusions

This phase lays the groundwork for advanced modeling, optimization, and predictive analysis in subsequent phases.

🔗 Integration with Phase 1
Phase 1 → Established data processing & benchmarking foundation
Phase 2 → Introduces derived metrics & analytical intelligence

Together, they form a cohesive pipeline transitioning from data → metrics → insights.

**Author:** [Kartik Thakkar](https://github.com/Kartikthakkarr)
