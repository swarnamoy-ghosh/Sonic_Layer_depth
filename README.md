# 🌊 Prediction of Sonic Layer Depth in the Bay of Bengal using Machine Learning

<p align="center">
  <img src="" alt="Sonic Layer Depth" width="500"/>
</p>

---

## 📘 Overview

This project explores a **machine learning-based framework** for predicting **Sonic Layer Depth (SLD)** in the **Bay of Bengal** using **satellite-accessible surface parameters**. It aims to bridge the observational gap between surface ocean data and subsurface acoustics, with potential applications in:

- 🌐 Oceanography  
- 🛥 Naval operations  
- 📡 Underwater communication  
- 🌎 Climate modelling  

---

## 🧠 Key Highlights

- ✅ Developed & evaluated **13 ML models** (Linear, Tree-based, Ensemble, ANN)
- 🔍 Feature reduction via **Principal Component Analysis (PCA)**
- 🌐 Data from **GLORYS12V1** & **ERA5** (1993–2020)
- 🧭 Analysis over **4 locations** in the Bay of Bengal
- 🧮 Best performance by **Artificial Neural Networks (ANN)**  
- 🌐 Open for real-time integration using satellite feeds

---

## 🧪 Machine Learning Models Used

| Category        | Models                                                           |
|----------------|------------------------------------------------------------------|
| Linear          | MLR, Ridge, Lasso, Elastic Net                                  |
| Non-linear      | Polynomial Regression (Deg 2 & 3), KNN                           |
| Ensemble        | Bagging, Random Forest, Gradient Boosting                       |
| Deep Learning   | Multilayer Perceptron (MLP)     |

---

## 📊 Input Features

- 🌡 Sea Surface Temperature (SST)  
- 💧 Sea Surface Salinity (SSS)  
- 📏 Sea Surface Height (SSH)  
- 🌀 Wind Speed at 10m (W10)  
- 🌫 Air Temperature at 2m (AIRT)  
- 🔥 Net Heat Flux (QNET)  
- 🌧 Freshwater Flux (EMP)  
- 🎯 Surface Sound Speed (SSC)  

---

## 📍 Study Locations

| Latitude | Region            |
|----------|--------------------|
| 4°N      | Southern BoB       |
| 8°N      | Southern-Central   |
| 12°N     | Central BoB        |
| 15°N     | Northern BoB       |

---

## 📈 Results Summary

- ANN models best at generalization and handling complex patterns  
- Linear models competitive in northern regions (simpler stratification)  
- PCA enhanced ensemble model stability  
- Unified model across all locations feasible using ANN  

---

## 🔮 Future Work

- Real-time deployment with live satellite feeds  
- Expansion to other ocean basins  
- Integration with acoustic propagation models  
- Testing with alternative ML architectures (e.g., Transformers, XGBoost)  

---

## 👩‍🔬 Authors

- **Swarnamoy Ghosh** (PG/05/MSTSTDS/2023/002)  
- **Debargho Chatterjee Ganguly** (PG/05/MSTSTDS/2023/004)  

🎓 M.Sc.(Tech) Statistics and Data Science  
🧮 Department of Mathematics, Adamas University  
👨‍🏫 Supervisor: Dr. Sudip Jana

---

## 🗂 Repository Structure

```bash
├── data/                  # Processed datasets (GLORYS & ERA5)
├── notebooks/             # Jupyter notebooks for EDA & modeling
├── figures/               # Visualizations & result plots
├── results/               # Evaluation metrics, reports
└── README.md              # This file
