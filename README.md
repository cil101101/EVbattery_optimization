# EV Charging Behavior Analysis and Prediction

This project analyzes a simulated dataset of Electric Vehicle (EV) charging sessions to uncover behavioral patterns and predict both **charging cost** and **energy consumption**. It is designed as part of the MA336 university coursework, focusing on applying data science techniques to real-world problems.

## 📌 Project Objectives

- ✅ Clean and preprocess the EV charging dataset
- 📊 Perform exploratory data analysis (EDA) and visualizations
- 🤖 Apply unsupervised learning (clustering) to segment EV usage patterns
- 🔮 Use machine learning models to predict:
  - Charging Cost
  - Energy Consumption

---

## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn` (KMeans, Linear Regression, DecisionTreeRegressor)
  - `datetime` for date/time handling

---

## 🗃️ Dataset Overview

The dataset (`ev_charging_patterns.csv`) includes features like:

- `Charging Start Time`, `Charging End Time`
- `Battery Capacity (kWh)`, `Energy Consumed (kWh)`
- `Charging Duration`, `Charging Rate`, `Charging Cost`
- `Temperature`, `Vehicle Age`

Each row represents a single charging session.

---

## 🚀 Getting Started

### Prerequisites

- Python installed (recommended: via [Anaconda](https://www.anaconda.com/))
- Clone or download this repository
- Place the dataset `ev_charging_patterns.csv` in the same directory as the notebook

### Installation

Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt

