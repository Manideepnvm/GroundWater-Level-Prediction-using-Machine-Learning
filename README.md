# 💧 Groundwater Level Prediction using Machine Learning  
<p align="right"><b>By Manideep Nvm</b></p>

---

## 🌍 Overview
This project aims to **predict groundwater levels** using advanced **Machine Learning models — CNN and LSTM**.  
It leverages **time-series climatic data** such as rainfall, temperature, humidity, and soil moisture to capture temporal and spatial dependencies influencing groundwater fluctuations.  
The system is designed to assist **farmers, researchers, and policymakers** in sustainable groundwater management through **accurate and interpretable predictions**.

---

## 🎯 Objectives
- To forecast groundwater levels using **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)** models.  
- To analyze the relationship between **climate variables and groundwater dynamics**.  
- To visualize predictions through an **interactive Streamlit dashboard** for real-time monitoring.  

---

## 🧩 Project Workflow
1. **Data Collection:**  
   - Historical groundwater, rainfall, and temperature datasets collected from public hydrological data sources.  

2. **Data Preprocessing:**  
   - Data cleaning, normalization, missing value imputation, and time-series reshaping for model training.  

3. **Feature Engineering:**  
   - Creation of lag features, moving averages, seasonal indicators, and temporal encoding to improve prediction accuracy.  

4. **Model Implementation:**  
   - **CNN Model:** Extracts spatial patterns and short-term dependencies.  
   - **LSTM Model:** Captures long-term temporal relationships in sequential groundwater data.  
   - Combined **CNN–LSTM Hybrid Model:** Utilized to enhance pattern recognition and predictive power.  

5. **Model Evaluation:**  
   - Metrics Used: RMSE, MAE, and R².  
   - Best performing model: **LSTM**, due to its strong handling of sequential dependencies.  

6. **Visualization & Dashboard:**  
   - Streamlit dashboard displays **actual vs predicted water levels**, **trend plots**, and **correlation heatmaps**.  

---

## 🧠 Deep Learning Models Used
| Model | Description | Purpose |
|--------|--------------|----------|
| **CNN (Convolutional Neural Network)** | Learns spatial patterns and short-term variations | Detects local trends |
| **LSTM (Long Short-Term Memory)** | Captures long-term dependencies and sequential relationships | Forecasts time-series data |
| **CNN–LSTM Hybrid** | Combines strengths of CNN and LSTM | Improves both accuracy and temporal awareness |

---

## 📈 Evaluation Metrics
| Metric | Description |
|---------|--------------|
| **RMSE** | Measures average magnitude of prediction error |
| **MAE** | Measures average absolute difference between actual and predicted values |
| **R²** | Indicates the proportion of variance explained by the model |

---

## 🧰 Tools & Technologies
- **Languages:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn  
- **Visualization:** Streamlit  
- **Framework:** Jupyter Notebook / VS Code  

---

## 🧮 Project Structure
