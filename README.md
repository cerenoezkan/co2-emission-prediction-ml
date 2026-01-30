# 🌍 AI-Based Sustainable Development Planning  
## Multi-Country CO₂ Emission Prediction Model – Turkey Case Study

This project focuses on predicting **per capita CO₂ emissions** using a **machine learning–based regression approach**, aligned with **UN Sustainable Development Goal 13 (Climate Action)**.

The study employs a **multi-country dataset** to improve model generalization and examines **Turkey** as a specific case study.

---

## 🎯 Objective

- Predict **per capita CO₂ emissions** using socio-economic and energy-related indicators  
- Build a **robust multi-country regression model**  
- Analyze results specifically for **Turkey (2010–2023)**  
- Provide **policy recommendations** aligned with **SDG 13 – Climate Action**

---

## 📊 Dataset

- **Source:** Our World in Data (OWID) – CO₂ Dataset  
- **Period:** 2010–2023  
- **Coverage:** Multiple countries  

### Variables Used
**Target Variable**
- `co2_per_cap` – CO₂ emissions per capita (tons)

**Selected Features**
- `en_per_cap` – Energy consumption per capita  
- `gni_per_cap` – Gross National Income per capita  
- `cereal_yield` – Cereal yield  
- `pop_urb_aggl_perc` – Urban agglomeration ratio  
- `urb_pop_growth_perc` – Urban population growth rate  

---

## 🧠 Methodology

- Exploratory Data Analysis (EDA)
  - Correlation matrix
  - Pairplot analysis
- Outlier removal (e.g., UAE)
- **Model:** Random Forest Regressor
- **Train/Test Split:** 80% / 20%

### Evaluation Metrics
- R² Score  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)

---

## 📈 Results

- **R² Score:** 0.968  
- **RMSE:** ≈ 0.78 tons  

The model explains approximately **96.8%** of the variance in CO₂ emissions, indicating high predictive performance.

---

## 🇹🇷 Turkey Case Study

- Period: 2010–2023  
- CO₂ emissions per capita decreased from **~4.5 tons** to **~3.6 tons**
- Reflects positive impacts of:
  - Renewable energy investments  
  - Energy efficiency policies  

---

## 🖼️ Visualizations

### Correlation Matrix
![Correlation Matrix](figures/correlation_matrix.png)

### Pairplot of Selected Variables
![Pairplot](figures/pairplot.png)

### Model Prediction vs Actual Values
![Model Performance](figures/model_performance.png)

### Turkey CO₂ Emission Trend
![Turkey Trend](figures/turkey_trend.png)

---

## 🏛️ Policy Recommendations (SDG 13)

1. **Increase Energy Efficiency** in industry and housing  
2. **Strengthen Renewable Energy Investments**  
3. **Promote Green Growth Strategies**  
4. **Support Sustainable Urban Planning**

---

## ⚙️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📄 License

This project is developed for **academic purposes only**.
