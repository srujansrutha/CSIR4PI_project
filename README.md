# 🌧️ Rainfall Pattern Prediction Using CHIRPS High-Resolution Data

A data science and AI/ML project conducted during a 15-week internship at **CSIR Fourth Paradigm Institute (CSIR-4PI), Bangalore**. This project analyzes and predicts rainfall trends across India using satellite-derived CHIRPS data and machine learning models.

---

## 📌 Project Overview

This project focuses on analyzing seasonal and regional rainfall patterns in India using **CHIRPS** and **IMD** datasets from 2012–2023. It applies statistical and machine learning techniques to:
- Understand spatial and temporal rainfall variability.
- Compare satellite vs ground truth rainfall estimates.
- Predict future rainfall patterns for agriculture planning.

---

## 📊 Key Highlights

- 🔍 **Dataset**: CHIRPS high-resolution rainfall data (NetCDF format)  
- 🧠 **Techniques Used**: Statistical trend analysis, Random Forest Regression  
- 📍 **Scope**: Nationwide — North, South, East, West, Central regions  
- 🗓️ **Time Span**: 2012 to 2023, with predictions for 2025  
- 🔄 **Model**: Random Forest Regressor with seasonal/monthly feature engineering  
- 📉 **Forecast Output**: Predicted peak rainfall in **July 2025**, drop in Aug–Sep  

---

## 🧪 Tools & Technologies

- **Languages**: Python  
- **Libraries**: `xarray`, `pandas`, `numpy`, `matplotlib`, `seaborn`, `cartopy`, `scikit-learn`  
- **File Format**: `.nc` (NetCDF)  
- **Visualization**: Line charts, heatmaps, spatial maps  
- **Model Evaluation**: MSE, R², k-fold cross-validation  

---

## 🌦️ Key Insights

- **July** is the peak month for rainfall during the monsoon.
- **North & East India** receive the highest seasonal rainfall.
- **Central & South India** show moderate rainfall with regional variability.
- Predictive modeling shows a decline in rainfall post-2023, suggesting need for **adaptation in agriculture**.
- Heatmaps and region-wise plots expose clear seasonal trends from 2012–2023.

---

## 💡 Recommendations for Agriculture

- Schedule crop sowing around **July** to maximize yield.
- Use **rainwater harvesting** and **drip irrigation** during low-rainfall months.
- Rotate crops and adopt **drought-resistant varieties** post-monsoon.
- Diversify income in rainfed regions (e.g., poultry, agroforestry).

---

## 🗂️ Folder Structure

Rainfall-Prediction-CHIRPS/
│
├── data/ # Raw CHIRPS NetCDF files
├── notebooks/ # Jupyter notebooks with code and EDA
├── models/ # ML models and evaluation metrics
├── visualizations/ # Generated rainfall plots and maps
└── README.md # Project overview and documentation

---

## 📚 References

- [CHIRPS Dataset](https://www.chc.ucsb.edu/data/chirps)
- [India Meteorological Department](https://www.imd.gov.in)
- CSIR-4PI Reports on Rainfall Prediction
- WMO Guidelines for Climate Modeling

---

## 👨‍💻 Author

**J. Srujan Vishwakarma**  
B.E. Artificial Intelligence & Data Science  
CMR Institute of Technology, Bangalore  
Intern @ CSIR Fourth Paradigm Institute (CSIR-4PI)  
Email: *srujansrutha01@gmail.com*

---

## 📝 License

This project is for educational and research purposes. Feel free to fork, explore, and cite!

