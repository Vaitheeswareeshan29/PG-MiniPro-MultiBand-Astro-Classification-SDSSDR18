# 🌌 PG Mini Project – Multi-Band Classification and Analysis of Astrophysical Objects Using SDSS DR18

> 🎓 *Postgraduate Mini Project | Department of Computer Science, Bharathiar University*

---

## 📘 Abstract

🔍 This project explores the **power of machine learning** in classifying astronomical objects using the **Sloan Digital Sky Survey Data Release 18 (SDSS DR18)** — one of the largest public astronomical datasets 🌠. Our objective is to classify **stars ⭐**, **galaxies 🌌**, and **quasars 🌟** by learning from multi-band photometric and spectral data.

By leveraging **supervised ML techniques**, we demonstrate how massive-scale data can be mined for hidden patterns, and how optimal model selection can drive **data-driven discovery** in astronomy 🚀.

---

## 🧠 Keywords

`Multi-band Classification` • `Astronomical Data Analysis` • `SDSS DR18` • `Star-Galaxy-QSO Classification` • `Machine Learning` • `Big Data` • `Sky Survey` 🌌

---

## 🔍 Introduction

🧬 The universe is vast, and so is the data collected by astronomical surveys! Among them, the **SDSS DR18** has emerged as a game-changer — providing billions of data points related to stars, galaxies, and quasars.

🌌 However, traditional analysis methods can’t keep up with such volume. Our project bridges this gap using **machine learning** to:
- Automate classification 
- Discover hidden relationships 
- Support astronomers with actionable insights 🌍

---

## 🛠️ Methodology

The project follows a **systematic pipeline** :

1. 📦 **Installation** of tools: `astroquery`, `pandas`, `scikit-learn`, `matplotlib`
2. 🛰 **Data Retrieval** using SQL queries from SDSS SkyServer
3. 🧹 **Data Cleaning** – handling missing values, scaling, encoding
4. 🧪 **Feature Engineering** – color indices (e.g., g-r, r-i), z-scores
5. 📊 **EDA** – KDE plots, PCA, sky density maps, redshift patterns
6. 🤖 **Model Building** – ML model training with validation
7. 🧠 **Model Evaluation** – accuracy, precision, recall, F1-score
8. 🧑‍💻 **User Input Prediction** – classify new objects with best model

---

## 📊 Exploratory Data Analysis

🧮 We performed:
- Descriptive Statistics 📊 (mean, std, min, max)
- Correlation Matrix with Heatmap 
- Redshift Distribution via KDE 📈
- PCA for dimensionality reduction 🔄
- Sky Maps showing object distribution 🌠
- Z-score outlier detection 🚨

These insights guided our feature selection and model optimization process.

---

## 🤖 Machine Learning Models

We implemented and compared several classifiers:

| 🔢 Model                 | ✅ Performance |
|--------------------------|----------------|
| 🌲 Random Forest         | 🥇 Best Overall |
| 🧭 K-Nearest Neighbors   | High Accuracy |
| 🌄 Gradient Boosting     | Competitive |
| 🌴 Decision Tree         | Moderate |
| 📉 Logistic Regression   | Poor for QSO |
| 🧮 Naive Bayes           | Weak Results |

Evaluation Metrics:
- 🔍 Accuracy
- 📊 Confusion Matrix
- 🎯 Precision / Recall / F1-score
- 📈 ROC curves (optional)

---

## 📈 Results and Discussion

### 🎖️ **Top Performer:** `Random Forest`
- 🟢 Accuracy: `92%`
- 🌌 Galaxy: `F1-score 0.96`
- ⭐ Star: `F1-score 0.89`
- 🌟 Quasar: `F1-score 0.79`

📉 Logistic Regression & Naive Bayes struggled, especially with overlapping data like quasars vs. stars.

📊 **Visual Results:**
- Accuracy comparison bar chart
- Confusion matrix heatmap
- Redshift KDE plots
- Sky density visualizations

> 🧠 *Insight:* Color indices like `g-r` and `r-i` were crucial in separating object types.

---

## 🎯 Conclusion

This project:
- ✅ Successfully built a machine learning-based classifier for astronomical object types.
- 🌌 Showcased SDSS DR18's potential in research.
- 🔍 Proved Random Forest’s reliability in large-scale classification.
- 🧠 Set the foundation for future deep learning-based astrophysical research.

💡 **Future Work Ideas:**
- CNN-based classification from SDSS images 📷
- Time-series models for object variability ⏱️
- Redshift-based clustering & distance modeling 
