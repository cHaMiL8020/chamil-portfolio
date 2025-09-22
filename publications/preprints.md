# 📝 Preprints & Drafts

---

## 1. Comparative Evaluation of Lightweight Anomaly Detection Techniques Across Diverse Models and Multi-Modal Datasets for Autonomous Robotic Edge Platforms  
**Authors:** Chamil Oshan Abeysekara, Binura Laksara Widanagama, Kyandoghere Kyamakya  
**Affiliation:** Institute for Smart Systems Technologies, Universität Klagenfurt, Austria    
**Status:** Full benchmark study in preparation  

### 🔹 Abstract  
Autonomous robots require **on-device anomaly detection (AD)** under strict memory, compute, and energy constraints. While deep networks dominate accuracy, they are often impractical at the edge. This work outlines a **unified benchmark** for evaluating lightweight paradigms:  
- **Extreme Learning Machines (ELM)**  
- **Discrete Cellular Neural Networks (dCeNN)**  
- **Shallow CNNs (TinyML variants)**  
- **Rule-/logic-aware neuro-symbolic hybrids (ASP, Semantic Loss)**  

Benchmarks span **five open datasets** (IMS Bearing, NASA C-MAPSS, UCI HAR, MIT-BIH Arrhythmia, UCSD Pedestrian) and evaluate:  
- **Detection**: macro-F1, AUROC, precision/recall  
- **Efficiency**: latency, model size, CPU/RAM, energy per inference  
- **Rule-Consistency**: symbolic constraint violations  

Experiments target **Raspberry Pi 4 and Jetson Nano**, following **MLPerf Tiny** principles.  
Expected outcomes:  
- ELM/dCeNN excel on structured low-dimensional signals  
- Shallow CNNs remain strong for visual anomalies under tight footprints  
- Neuro-symbolic hybrids improve safety compliance in critical robotics scenarios  

### 🔹 Contribution  
Provides a **literature-grounded benchmark protocol** for edge AD, aiming to release **open-source code, artifacts, and reproducible evaluation** for the robotics research community.  

---

