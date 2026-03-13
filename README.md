# 🌫️ Air Quality Index (AQI) Prediction using Python

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-green?style=flat-square&logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

> Predicting Air Quality Index (AQI) using machine learning techniques in Python — analyzing pollutant data to forecast air quality levels and help identify environmental health risks.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [What is AQI?](#-what-is-aqi)
- [Dataset](#-dataset)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Workflow](#-workflow)
- [Models Used](#-models-used)
- [Results](#-results)
- [How to Run](#-how-to-run)
- [Author](#-author)

---

## 📖 Overview

Air pollution is one of the most critical environmental challenges of the 21st century. This project builds a machine learning model to **predict the Air Quality Index (AQI)** based on concentrations of key air pollutants. By accurately predicting AQI, we can:

- Provide early warnings for hazardous air quality events
- Help governments and citizens make informed decisions
- Analyze pollution trends across regions and time periods

---

## 🌍 What is AQI?

The **Air Quality Index (AQI)** is a standardized scale used to communicate how polluted the air currently is or how polluted it is forecast to become.

| AQI Range | Category | Health Impact |
|-----------|----------|---------------|
| 0 – 50 | Good | Little or no risk |
| 51 – 100 | Moderate | Acceptable; some concern for sensitive groups |
| 101 – 150 | Unhealthy for Sensitive Groups | Sensitive people may experience effects |
| 151 – 200 | Unhealthy | Everyone may begin to experience effects |
| 201 – 300 | Very Unhealthy | Health alert — serious effects for everyone |
| 301+ | Hazardous | Emergency conditions |

---

## 📊 Dataset

The dataset contains readings of major air pollutants used to compute AQI:

| Feature | Description |
|---------|-------------|
| `PM2.5` | Fine particulate matter (≤ 2.5 µm) |
| `PM10` | Coarse particulate matter (≤ 10 µm) |
| `NO` | Nitric Oxide |
| `NO2` | Nitrogen Dioxide |
| `NOx` | Nitrogen Oxides |
| `NH3` | Ammonia |
| `CO` | Carbon Monoxide |
| `SO2` | Sulfur Dioxide |
| `O3` | Ozone |
| `Benzene` | Benzene concentration |
| `Toluene` | Toluene concentration |
| `AQI` | Target variable — Air Quality Index |
| `AQI_Bucket` | AQI category label |

---

## 🛠️ Tech Stack

```
Python 3.8+
├── pandas          — Data loading & manipulation
├── numpy           — Numerical operations
├── matplotlib      — Data visualization
├── seaborn         — Statistical plots
├── scikit-learn    — ML models & preprocessing
└── Jupyter Notebook — Interactive development environment
```

---

## 📁 Project Structure

```
aqi-prediction-python/
│
├── Predicting_Air_Quality_Index_using_Python.ipynb   # Main notebook
└── README.md                                          # Project documentation
```

---

## 🔄 Workflow

```
1. Data Loading
        ↓
2. Exploratory Data Analysis (EDA)
   ├── Shape, dtypes, null values
   ├── Distribution plots
   └── Correlation heatmap
        ↓
3. Data Preprocessing
   ├── Handling missing values
   ├── Feature selection
   └── Train-test split
        ↓
4. Model Training
   ├── Multiple regression models
   └── Hyperparameter tuning
        ↓
5. Model Evaluation
   ├── R² Score
   ├── MAE / RMSE
   └── Prediction vs Actual plots
        ↓
6. Results & Conclusions
```

---

## 🤖 Models Used

| Model | Type |
|-------|------|
| Linear Regression | Baseline regression |
| Random Forest Regressor | Ensemble — tree based |
| Decision Tree Regressor | Tree based |
| K-Nearest Neighbors | Instance based |

---

## 📈 Results

The models were evaluated using standard regression metrics:

- **R² Score** — measures how well predictions fit actual AQI values
- **MAE (Mean Absolute Error)** — average prediction error magnitude
- **RMSE (Root Mean Squared Error)** — penalizes larger errors more heavily

> Refer to the notebook for detailed metric comparisons and visualization plots.

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/uddhav05-cyber/aqi-prediction-python.git
cd aqi-prediction-python
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook Predicting_Air_Quality_Index_using_Python.ipynb
```

### 4. Run All Cells

In Jupyter: **Kernel → Restart & Run All**

---

## 👨‍💻 Author

**Uddhav Bhople**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-uddhav--bhople-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/uddhav-bhople/)
[![GitHub](https://img.shields.io/badge/GitHub-uddhav05--cyber-black?style=flat-square&logo=github)](https://github.com/uddhav05-cyber)
[![Email](https://img.shields.io/badge/Email-uddhavbhople5%40gmail.com-red?style=flat-square&logo=gmail)](mailto:uddhavbhople5@gmail.com)

> BTech Computer Engineering | DY Patil University, Pune
> Software Engineering Student & Aspiring AI Engineer

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <i>If you found this project helpful, please consider giving it a ⭐</i>
</p>
