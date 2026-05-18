# 🏢 Building Inefficiency Anomaly Detection

Machine learning project for detecting abnormal building energy behavior using clustering (K-Means) and anomaly detection techniques (Isolation Forest, DBSCAN).
Residual Energy with benchmark to: EUI (energy use per area), HistGradBoosting <br>

## 📌 Overview
This project explores how AI can identify inefficient operational patterns in buildings from energy-related sensor and operational data. The notebook demonstrates an end-to-end workflow including preprocessing, exploratory analysis, anomaly detection, and visualization.

The goal is to support:
- Smart building monitoring
- Energy efficiency optimization
- Early fault detection
- Sustainability & decarbonization initiatives

Categories:
- C1: low energy intensity, low residual load -> efficient
- C2: high energy intensity, but strongly explained by weather/time -> normal weather-driven
- C3: high energy intensity, high residual load, especially at mild weather or night -> inefficient (what we are highlighting!)

---

## ⚙️ Key Features
Dataset source: https://www.kaggle.com/c/ashrae-energy-prediction <br>
- Data preprocessing & feature engineering
- Exploratory data analysis (EDA)
- Time-series anomaly detection
- ML-based outlier identification
- Visualization of abnormal operational behavior
- Energy inefficiency insights

---

## 🧠 Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📊 Project Highlights
- Built an anomaly detection workflow for building operational inefficiency analysis
- Applied machine learning techniques to identify unusual consumption behavior
- Visualized anomalies to improve interpretability and operational insights
- Demonstrated AI applications for energy and sustainability use cases

---
## Conclusion

The clustering and anomaly detection analysis reveals clear patterns in building energy behavior and successfully identifies buildings with potentially inefficient operational profiles.

#### Key Findings
The dataset naturally separates into three main building behavior groups:
1) C1 – Efficient buildings
Buildings with relatively stable and lower energy consumption patterns.
2) C2 – High energy but weather-driven
Buildings whose energy usage increases significantly depending on external conditions such as temperature or seasonal effects.
3) C3 – High energy regardless of weather
Buildings with consistently high energy consumption independent of weather influence, indicating potential operational inefficiency or hidden faults. Healthcare, Parking, and Other unclassified.

<img width="1296" height="379" alt="image" src="https://github.com/user-attachments/assets/9f2575dd-b3ba-4079-841b-7b58b97ab2f8" /><br />
<img width="1292" height="476" alt="image" src="https://github.com/user-attachments/assets/caf0e3fe-5320-4098-b83c-8d7df2334e10" /><br />
<img width="877" height="525" alt="image" src="https://github.com/user-attachments/assets/e8c749a1-b8bf-4372-896c-55b4dc090ab4" /><br />

---

## 📂 Repository Structure
```bash
├── Final.ipynb        # Main notebook
├── dataset/           # Input datasets (if applicable)
└── README.md
