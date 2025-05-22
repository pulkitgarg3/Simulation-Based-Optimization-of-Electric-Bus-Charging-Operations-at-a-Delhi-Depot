# Simulation-Based Optimization of Electric Bus Charging Operations

## 📌 Overview

This project explores how a major electric bus depot in Delhi can optimize its charging operations using a **discrete-event Monte Carlo simulation** built in Python. By combining real-world data from over **330 charging sessions** and stakeholder insights, the study simulates depot behavior across three scenarios:

- **Baseline:** 110 e-buses and 21 chargers (current setup)
- **Scenario 1:** Expanded to 25 chargers
- **Scenario 2:** Fleet expanded to 130 buses without increasing chargers

The aim? **Reduce wait times**, **maximize charger utilization**, and **guide smarter infrastructure investments**.

---

## 🧠 Motivation

Electric buses promise clean, cost-efficient urban transit—but charging them efficiently is the real challenge. Delhi's depots struggle with high peak loads, congestion, and inflexible schedules. This simulation bridges the gap between **on-ground complexity and scalable planning**, helping policy-makers make data-backed decisions.

---

## 🛠️ Tools & Tech Stack

- **Python**
  - `SimPy` for discrete-event simulation
  - `Pandas` for data handling
  - `Matplotlib` and `Seaborn` for visualizations
  - `NumPy` for Monte Carlo randomization
- **Data Sources**
  - Real-world charging logs from a 110-bus fleet over 3 days
  - Route schedules from DTC & Moovit
  - Field visits and qualitative inputs from depot staff

---

## 📊 Key Insights

- ⚡ **Baseline analysis** validated simulation accuracy with <5% deviation from real wait times.
- 📈 **Adding 4 chargers** (21 → 25) reduced overnight wait time by 23 minutes on average.
- 🛑 **Fleet expansion without charger growth** led to a 38-minute increase in wait time and incomplete overnight charging.
- 🔁 Identified **bottleneck hours** (1 PM to 3 PM, and 10 PM to 3 AM) with 100% charger saturation.

---

## 🔍 Core Performance Metrics

| Metric                 | Baseline | Scenario 1 (More Chargers) | Scenario 2 (More Buses) |
|------------------------|----------|-----------------------------|--------------------------|
| R1 Wait Time (min)     | 19.1     | 25.8                        | 19.0                     |
| R2 Wait Time (min)     | 137.4    | 114.3                       | 175.3                    |
| SOC After Overnight (%)| 100      | 100                         | 98.4                     |

---

## 📷 Visuals & Highlights

- Hourly Charger Utilization Graphs
- Wait Time Distributions (Top-Up & Overnight)
- Energy Delivery Histogram (per bus)
- Scenario Comparison Bar Charts

---

## 🎯 Impact & Applications

- Designed as a **decision-support tool** for transit authorities.
- Helps evaluate **smart scaling** of chargers alongside fleet expansion.
- Supports sustainable electric mobility in **high-density urban settings**.

---

## 👨‍💻 Author

**Pulkit Garg**  
MBA (Business Economics) | University of Delhi  
Specialization: Marketing & Analytics  

---

## 📢 Note

This project was completed as part of an academic research assignment under the guidance of **Dr. Megha Jacob**. It blends field work, simulation modeling, and energy analytics—an ideal showcase of data-driven policy and operations research.

---

## 🔮 Future Scope

- Incorporating **real-time traffic & weather variability**
- Modeling **charging curves for different charger types**
- Integrating **TOU (Time-of-Use) electricity pricing strategies**

