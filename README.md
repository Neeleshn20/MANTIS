
# 🛡️ MANTIS - AI-Based Predictive Maintenance and Supply Chain Mapping (PoC v1.0)

**Project Type:** Defense AI/ML Proof-of-Concept  
**Developer:** [Your Name]  
**Date:** May 2025  
**Incubation Support:** CEDI, NIT Trichy  
**Submission for:** Indian Army Design Bureau PDS 65 + 66

---

## 📌 Overview

**MANTIS** (Monitoring and Analytics for Networked Tactical Infrastructure Sustainment) is a modular AI-based system built to enhance:
- **Predictive Maintenance** of mission-critical assets,
- **Spare Inventory Demand Forecasting**, and
- **Supply Chain Network Risk Mapping** for defense logistics.

This Proof-of-Concept (PoC) demonstrates how machine learning and network analytics can be applied to improve logistics resilience in real-world military contexts.

---

## 🧭 Directory Structure

```
MANTIS/
│
├── App/                        # Final Streamlit Application
│   ├── mantis_app.py
│   └── mantis_logo.png
│
├── Data/                       # Synthetic Input Datasets
│   ├── equipment_logs.csv
│   ├── spare_inventory.csv
│   ├── route_map.csv
│   └── scm_supplier_data_final.csv
│
├── Models/                     # Trained ML Models (.pkl)
│   ├── equipment_failure_model.pkl
│   └── spare_demand_forecast_model.pkl
│
├── Notebooks/                  # Development Notebooks
│   ├── predictive_maintenance.ipynb
│   └── supply_chain_graph.ipynb
│
├── Anomaly_Outputs/            # Detected Anomalies from ML
│   ├── equipment_anomalies.csv
│   ├── spare_inventory_anomalies.csv
│   ├── route_map_anomalies.csv
│
├── README.md                   # Project Documentation
└── requirements.txt            # Required Python Libraries
```

---

## 🚀 How to Run the App

1. **Install requirements**  
   Run this in your terminal:

   ```bash
   pip install -r requirements.txt
   ```

2. **Start Streamlit App**

   ```bash
   cd App
   streamlit run mantis_app.py
   ```

3. **Upload CSVs**  
   Use the sidebar to navigate across:
   - **Predictive Maintenance**
   - **Spare Inventory Forecast**
   - **Supply Chain Mapping**
   - **Anomaly Insights**

---

## 🔍 Module Descriptions

### 1. Predictive Maintenance
- Inputs: `equipment_logs.csv`
- Output: Predicts likelihood of failure using trained ML model.
- Purpose: Preemptively identify critical equipment at risk.

### 2. Spare Inventory Forecasting
- Inputs: `spare_inventory.csv`
- Output: Demand forecast for spares using time-series + ML.
- Purpose: Optimize spare stock levels and reduce shortages.

### 3. Supply Chain Mapping
- Inputs: `scm_supplier_data_final.csv`
- Output: Dynamic graph showing tier-wise supplier network.
- Features: Risk-based node coloring, alternate supplier mapping.

### 4. Anomaly Insights
- Inputs: Pre-generated anomaly CSVs from `/Anomaly_Outputs`
- Output: Visualizes numeric anomalies using histograms and tables.
- Purpose: Highlight unexpected patterns and vulnerabilities.

---

## ⚙️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python (Pandas, scikit-learn, NetworkX, Matplotlib, Seaborn)
- **Models:** Trained `.pkl` files for inference
- **Deployment:** Local (PoC)

---

## 📎 Notes

- All datasets are **synthetic** but modeled realistically for demonstration.
- Designed for future adaptation to secure defense environments.
- Modularized to allow rapid updates and model retraining.

---

## 📧 Contact

For further queries or walkthroughs, please contact:  
**N Naga Neelesh**  
Email: nnaganeelesh@gmail.com 
Phone: +91 9344550991 
Affiliation: B.Tech(Production Engineering), NIT Trichy

---
