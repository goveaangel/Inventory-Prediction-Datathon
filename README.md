# 🧠 Predictive Demand Modeling for Inventory Optimization (Anonymized Datathon)

This repository contains the anonymized and public version of a forecasting framework developed during an academic–industrial datathon.  
The objective was to design **data-driven models** to predict weekly product demand and support **inventory optimization**.

---

## 📂 Repository Structure
```bash
Datathon_Anonymized_Version.pdf
notebooks/
│
├── EDA.ipynb                 
├── season_temp_anom.ipynb   
│
├── LSTM/
│   ├── LSTM_1.ipynb         
│   └── LSTM_2.ipynb          
│
├── prophet/
│   └── prophet.ipynb         #
│
├── sarima/
│   ├── sarima_Articulo1.ipynb
│   ├── sarima_Articulo2.ipynb
│   ├── sarima_Articulo3.ipynb
│   ├── sarima_Articulo4.ipynb
│   └── sarima_Articulo5.ipynb
```

---

## ⚙️ Project Overview

This project integrates **Exploratory Data Analysis (EDA)** and **three forecasting approaches**:

| Model | Description | Libraries |
|-------|--------------|------------|
| **SARIMA** | Captures linear seasonality and trend | `statsmodels` |
| **Prophet** | Additive model with trend and seasonality components | `prophet` |
| **LSTM** | Deep recurrent model for non-linear patterns | `tensorflow`, `keras` |

Each method was evaluated on **weekly aggregated product-level series**, using synthetic or anonymized data aligned with confidentiality requirements.

---

## 📊 Methodology Summary

1. **Data Preprocessing**
   - Weekly aggregation per product
   - Outlier treatment and normalization
   - Missing value imputation and temporal reconstruction

2. **EDA**
   - Time-based exploration (annual, monthly, weekly views)
   - Detection of anomalies and seasonal cycles

3. **Modeling**
   - SARIMA, Prophet, and LSTM architectures trained and compared
   - Model-specific tuning and validation

4. **Results**
   - Comparative evaluation of time-series forecasting performance
   - Discussion on model interpretability and deployment feasibility

---

## 📘 Report

The public report is available in PDF format:

**[`Datathon_Anonymized_Version.pdf`](Datathon_Anonymized_Version.pdf)**  
It summarizes methodology, results, and conclusions using **synthetic figures and anonymized data**.

---

## 🧩 Technologies Used

- **Python 3.10+**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Statsmodels**, **Prophet**
- **TensorFlow / Keras**
- **Scikit-learn**

---

## 🔒 Confidentiality Statement

This repository contains a **public and anonymized** version of the original work.  
All company names, customer/product identifiers, and real operational data have been removed or replaced with **synthetic equivalents**.

---

## 👥 Authors

- **José Ángel Govea García**  
- **Daniel Alberto Sánchez Fortiz**  
- **Diego Vértiz Padilla**  
Tecnológico de Monterrey, Campus Guadalajara

---

## 🧾 License

This project is shared under a **non-commercial academic license**.  
Do not use or distribute real data or any derived confidential material.
