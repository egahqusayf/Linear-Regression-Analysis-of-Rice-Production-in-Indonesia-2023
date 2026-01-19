# Linear Regression Analysis of Rice Production in Indonesia (2023)

## Overview
This project analyzes and predicts rice production across Indonesian provinces
using **Linear Regression**, based on harvested area data from **Badan Pusat Statistik (BPS)**.

All experiments and analysis are conducted using **Google Colab** to ensure
reproducibility and ease of access.

---

## Dataset
- Source: Badan Pusat Statistik (BPS) Indonesia
- Year: 2023
- Features:
  - Harvested Area (ha)
  - Rice Production (tons)
- Data Level: Province

Dataset is stored in the `/data` directory.

---

## 🧠 Methodology
1. Data loading directly from GitHub into Google Colab
2. Exploratory Data Analysis (EDA)
3. Train-test split
4. Linear Regression modeling
5. Model evaluation using MAE, RMSE, and R²
6. Visualization and asset generation

---

## 📈 Results

| Metric |     Value    |
|--------|--------------|
| MAE    | 66,269 tons  |
| RMSE   | 106,381 tons |
| R²     | 0.995        |

The model explains approximately **99.5% of the variance** in rice production.

---

## Limitations
- Single independent variable
- Does not consider climate, productivity, or technology

---

## Future Work
- Multivariate regression (add yield, rainfall)
- Time-series analysis
- Spatial visualization by province

---

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

