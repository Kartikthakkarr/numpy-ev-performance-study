# 🚗 EV Performance Engineering Study (2025)

⚡ **An engineering deep-dive into the 2025 EV market using NumPy-based modeling and stochastic simulations.**

---

## 📌 The "Why" Behind the Project

Most EV comparisons stop at surface-level metrics (Price vs. Top Speed).

I wanted to go deeper.

This project treats EV specifications as a **physics problem**, not just a dataset. By leveraging NumPy for vectorized computation, I built a framework to quantify:

* ⚡ Computational efficiency
* 🧠 Derived engineering intelligence
* 🔋 Long-term reliability

---

## 🚀 Key Insights (Highlights)

* ⚡ **The 400km Benchmark:**
  A clear "survival line" for 2025 — 229 vehicles cluster around this threshold

* 🔋 **Engineering vs Marketing:**
  *Dacia Spring Electric 45* leads in efficiency (~109 Wh/km), proving weight optimization beats battery size

* 📉 **The Degradation Tipping Point:**
  ~18–20% battery degradation significantly reduces long-distance usability for budget EVs

---

## 📊 Project Phases

### Phase 1: Numerical Foundations & Vectorization

* Converted raw dataset into **NumPy arrays**
* Eliminated Python loops → improved computation efficiency
* Established baseline metrics:

  * Energy density
  * Power-to-weight ratio

---

### Phase 2: Derived Metrics (Efficiency Index)

To move beyond raw specifications, I built a **Composite Engineering Score**:

* ⚡ Energy Utilization → *km/kWh*
* ⚖️ Performance-to-Weight Ratio

**Goal:** Identify "hidden gems" — vehicles delivering high performance without compromising efficiency

---

### Phase 3: Stochastic Simulation & Aging

* 🎲 Applied Monte Carlo-style simulations
* 🔋 Modeled battery degradation (0–20%)

**Objective:**
Evaluate how EV performance evolves after years of real-world usage

**Result:**
Some high-range vehicles degrade faster than expected, reducing long-term utility

---

## 🛠️ Technical Hurdles (Human Note)

One of the most challenging aspects was normalizing the **Torque-to-Weight ratio**.

The issue:
Battery chemistry differences affect discharge behavior, making raw comparisons unreliable.

**Solution:**
I designed a standardized Data Dictionary to enforce **consistent SI units**, ensuring fair and accurate modeling.

---

## 🧰 Tech Stack

* **Python 3.x**
* **NumPy** → Vectorized numerical computation
* **Pandas** → Data preprocessing
* **Matplotlib / Seaborn** → Visualization

---

## 📂 Project Structure

```id="l1d8f3"
data/                  # EV specifications (22 variables)
src/                   # Phase-wise analysis scripts
DATA_DICTIONARY.md     # SI units & variable definitions
```

---

## ▶️ How to Run

```bash id="5d5sm2"
# Clone the repository
git clone https://github.com/Kartikthakkarr/numpy-ev-performance-study

# Install dependencies
pip install -r requirements.txt

# Run analysis
python src/phase1_analysis.py
```

---

## 🏁 Final Note

This project reflects how I approach data analysis:

> Not just analyzing numbers — but understanding the **engineering reality behind them**.

---

## 👨‍💻 Author

**Kartik Thakkar**
Data Analyst Trainee | EV Engineering Enthusiast

Focused on combining **clean code, mathematical modeling, and real-world engineering insight**.

---

⭐ If you found this useful, consider starring the repository.

---
