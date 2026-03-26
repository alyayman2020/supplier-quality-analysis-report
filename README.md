# 🏭 Supplier Quality Analysis — Supply Chain Performance Project

> **Track:** Data Analyst Specialist Track  
> **Objective:** Evaluate supplier quality and plant performance to drive supply chain efficiency through data-driven insights.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)
- [Key Goals](#key-goals)
- [Repository Structure](#repository-structure)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [How to Use](#how-to-use)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🚀 Project Overview

This project performs a comprehensive quality audit across suppliers, products, and manufacturing plants. The analysis pipeline covers:

| Phase | Description |
|---|---|
| **Data Cleaning** | Standardizing and preprocessing raw supplier quality data |
| **EDA** | Uncovering defect trends, correlations, and performance outliers |
| **Visualization** | Interactive Tableau dashboard for executive-level exploration |
| **Reporting** | Actionable findings packaged into a comprehensive PDF report |

---

## 🎯 Key Goals

1. **Identify** top-performing vs. underperforming suppliers based on defect rate benchmarks.
2. **Analyze** defect and downtime patterns across products, plants, and supplier categories.
3. **Develop** data-driven strategies to optimize supply chain quality control.

---

## 📁 Repository Structure

```
📦 supplier-quality-analysis/
├── 📓 Final Project - Python Notebook.ipynb   # EDA, cleaning, statistical analysis
├── 📊 Final Project - Dashboard.twbx          # Interactive Tableau dashboard
└── 📄 Final Project - Report.pdf              # Full report with insights & recommendations
```

### File Descriptions

- **`Python Notebook.ipynb`** — End-to-end data pipeline: cleaning, preprocessing, visualizations, and statistical analysis of defect rates and downtime metrics.
- **`Dashboard.twbx`** — Tableau workbook with interactive filters for supplier, plant, category, and time period.
- **`Report.pdf`** — Executive summary with methodology, findings, and strategic recommendations.

---

## 🔍 Key Findings

| Finding | Detail |
|---|---|
| **High-Defect Suppliers** | Suppliers with defect rates >5% were primary drivers of delays and increased operational costs |
| **High-Risk Categories** | **Mechanical** and **Packaging** categories exhibited the highest defect concentrations |
| **Worst-Performing Plant** | **Detroit plant** recorded the highest defect volume, with a notable spike in **October** |
| **Seasonal Patterns** | Defect rates surged **mid-year** and in **Q4**, correlated with seasonal demand fluctuations |

---

## ✅ Recommendations

- **Supplier Prioritization** — Concentrate procurement on suppliers maintaining defect rates **< 1%**; phase out or audit high-defect vendors.
- **Quality Control Protocols** — Implement stricter incoming inspection processes for **Mechanical** and **Packaging** categories.
- **Plant-Level Intervention** — Conduct a root-cause analysis for the **Detroit plant**, targeting operational and process inefficiencies.
- **Predictive Monitoring** — Deploy predictive analytics models to proactively flag at-risk suppliers before defect escalation.

---

## 🛠 How to Use

### 1. Jupyter Notebook

```bash
# Install dependencies
pip install pandas matplotlib seaborn

# Launch notebook
jupyter notebook "Final Project - Python Notebook.ipynb"
```

**Requirements:** Python 3, `pandas`, `matplotlib`, `seaborn`

### 2. Tableau Dashboard

- Open `Final Project - Dashboard.twbx` in **Tableau Desktop** or **[Tableau Reader](https://www.tableau.com/products/reader)** (free).
- Use filters to drill down by supplier, plant, product category, or time period.

### 3. PDF Report

- Open `Final Project - Report.pdf` in any PDF viewer.
- Contains full methodology, visualizations, and executive recommendations.

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| **Python 3** | Data cleaning & statistical analysis |
| **pandas** | Data manipulation |
| **matplotlib / seaborn** | Exploratory visualizations |
| **Tableau** | Interactive dashboard |

---

## 👥 Team

| Name | Role |
|---|---|
| **Aly Ayman** | Team Member |
| **Nrmeen Farag** | Team Member |
| **Menna Mahmoud** | Team Member |
| **Mina Fawzy** | Team Member |

**Mentor:** Eng. Yasser Abd ElRahman

---

> 💡 *Found an issue or want to contribute? Feel free to open a pull request or raise an issue.*
