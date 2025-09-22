# 🔧 Industrial Predictive Maintenance – Atlas Axillia

---

## 🔹 Overview
This project focused on developing an **AI-driven predictive maintenance system** for Atlas Axillia, Sri Lanka. The goal was to reduce **unplanned downtime** and **optimize maintenance cycles** by detecting early signs of machine failure using vibration data.  

The system achieved significant **cost savings (~EUR 21,300 annually)** by enabling proactive maintenance interventions and extending equipment lifespan.  

🎥 [Watch Project Demo](https://youtu.be/SENkjP_EN58)  

---

## 🔹 Context
- **Type:** BSc (Hons) Mechatronic Engineering – Final Year Research Project
- **Year:** 2020 
- **Institution:** Atlas Axillia, Sri Lanka (Industry Partner)  
- **Team Role:** Lead developer – responsible for data pipeline design, model training, and dashboard integration.  

---

## 🔹 Tech Stack
- **Programming:** Python (NumPy, Pandas, Matplotlib, scikit-learn, TensorFlow)  
- **Data Handling:** PLC integration, real-time data collection  
- **Algorithms:** PCA, Mahalanobis distance, anomaly detection pipelines  
- **Deployment:** Jupyter Notebook prototype, reporting dashboards  

---

## 🔹 Methodology
1. **Data Collection**  
   - Vibration data captured from motors and bearings via PLCs.  
   - Preprocessing with normalization and noise reduction.  

2. **Feature Extraction**  
   - Principal Component Analysis (PCA) used to reduce dimensionality.  
   - Extracted dominant vibration patterns representing machine state.  

3. **Anomaly Detection**  
   - Mahalanobis Distance applied to detect deviations from baseline healthy state.  
   - Threshold tuning for early fault detection.  

4. **Visualization & Reporting**  
   - Interactive dashboards for real-time anomaly monitoring.  
   - Automated alerts to maintenance teams.  

---

## 🔹 Results & Impact
- 📊 **Accuracy:** Early detection of abnormal vibration patterns before visible breakdown.  
- 💰 **Economic Impact:** Estimated savings ~EUR 21,300 annually due to reduced downtime.  
- ⏱️ **Maintenance Cycle Optimization:** Improved scheduling → reduced unnecessary servicing.  
- 🏭 **Business Impact:** Increased reliability of factory operations.  

---

## 🔹 Challenges & Learnings
- **Noise in sensor data** required robust preprocessing.  
- **Trade-off** between sensitivity and false alarms → solved with careful threshold calibration.  
- Learned the importance of **deployability** and simplicity in industrial AI (lightweight models > complex deep nets).  

---

## 🔹 Links & Resources
- 📄 [Project Report (PDF)](../docs/reports/Preventive_Maintenance_Model_Using_AI.pdf)  
- 📓 [Jupyter Notebook (Prototype)](../docs/notebooks/FYP_Atlas_Predictive_Maintenance.ipynb)  
- 🎥 [Demo Video](https://youtu.be/SENkjP_EN58)  

---

## 🔹 Future Work
- Integration with **real-time streaming pipelines** (Kafka, MQTT).  
- Edge deployment on **Raspberry Pi / Jetson Nano** for onsite inference.  
- Incorporation of **deep learning methods (CNN, LSTM)** for richer time-series analysis.  
