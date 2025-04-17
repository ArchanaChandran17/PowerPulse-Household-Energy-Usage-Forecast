# ⚡️ PowerPulse: Predicting Household Energy Usage with ML

> *Smarter homes start with smarter energy forecasting.*  
> Predict, visualize, and optimize your household electricity consumption using machine learning.

---

![PowerPulse Banner](https://img.shields.io/badge/Energy-AI%20Powered-brightgreen) ![Python](https://img.shields.io/badge/Built%20With-Python-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 🚀 Project Snapshot

🔋 **PowerPulse** is your gateway to intelligent energy forecasting. Using machine learning, we dive deep into household electric power usage data, clean and crunch it, and predict future consumption patterns — all with the goal of energy efficiency and smarter living.

---

## 🎯 Goals

- 🔎 Understand patterns in power consumption  
- 🤖 Build predictive ML models  
- 📉 Reduce energy waste through insights  
- 📊 Visualize trends, anomalies & feature impact

---

## 🛠 Tech Stack

| Layer         | Tools Used                                  |
|--------------|----------------------------------------------|
| 💻 Language   | Python                                       |
| 📦 Libraries  | `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn` |
| 🧠 Models     | Linear Regression, Random Forest, Gradient Boosting, MLP |
| 📄 Notebook   | `new_p3.ipynb` for full analysis & modeling  |

---

## 📈 Key Features

- ✅ Outlier Detection & Capping
- 🔀 Feature Engineering (daily averages, rolling stats, etc.)
- ⚙️ Multiple Model Training with Comparison
- 🧪 Evaluation using RMSE, MAE, R²
- 📊 Visual Explorations: Boxplots, KDEs, Heatmaps

---

## 🧠 ML Performance Overview

| 🔍 Model          | 📉 RMSE | 📊 MAE | 🎯 R² Score |
|------------------|--------:|-------:|------------:|
| Random Forest     | **0.0280** | **0.0129** | **0.9993** |
| Gradient Boosting | 0.0343 | 0.0215 | 0.9990 |
| Neural Network    | 0.0330 | 0.0204 | 0.9990 |
| Linear Regression | 0.0403 | 0.0255 | 0.9985 |

✨ **Winner:** Random Forest steals the spotlight with the most accurate predictions.

---

## 📦 Dataset

- 🗂 **Source**: [UCI ML Repository – Individual Household Electric Power Consumption](https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption)
- 🏠 Minute-level measurements (2006–2010) of a single household's power usage

---

## 🔍 Visuals Sneak Peek

| 📌 Plot Type         | 🔍 Purpose                                |
|---------------------|-------------------------------------------|
| Boxplots            | Spot & cap outliers                        |
| KDE & Histograms    | Examine skew and distribution              |
| Heatmaps            | Uncover correlations                      |
| Bar Charts          | Compare model performance                |

---

## 🚦 How to Run the Project

```bash
# 1. Clone this repo
git clone https://github.com/your-username/PowerPulse

# 2. Navigate into project
cd PowerPulse

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run Jupyter Notebook
jupyter notebook new_p3.ipynb
