
# ⚡ Edge Forecasting with dCeNN + ELM + ASP (2024–2025)

---

## 🔹 Overview
This project investigates **lightweight forecasting and anomaly detection** for **edge devices** used in autonomous robots and Industry 4.0 systems.  
The approach integrates:  
- **Discrete Cellular Neural Networks (dCeNN)** for spatiotemporal feature extraction  
- **Extreme Learning Machines (ELM)** for fast, single-pass classification  
- **Answer Set Programming (ASP)** for rule consistency and symbolic reasoning  

The combination aims to deliver **efficient, interpretable, and rule-compliant anomaly detection** directly at the edge — without reliance on cloud computing.  

---

## 🔹 Context
- **Type:** MSc Thesis + Research Project  
- **Year:** 2024–2025  
- **Institution:** University of Klagenfurt, Austria  
- **Outcomes:**  
  - Extended abstract accepted at **AUTSYS 2025** (*Comparative Evaluation of Lightweight Anomaly Detection Techniques Across Diverse Models and Multi-Modal Datasets for Autonomous Robotic Edge Platforms*).  
  - Review paper in preparation: *A Critical and Comprehensive State of the Art Review on Combining Learning and Reasoning for Edge Anomaly Detection.*  

---

## 🔹 Tech Stack
- **Programming:** Python, PyTorch, scikit-learn  
- **Reasoning Frameworks:** Answer Set Programming (Clingo, NeurASP)  
- **Deployment Targets:** Raspberry Pi 4, Jetson Nano  
- **Datasets:**  
  - IMS Bearing (predictive maintenance)  
  - NASA C-MAPSS (aero-engine time-series)  
  - UCI HAR (human activity)  
  - MIT-BIH Arrhythmia (ECG)  
  - UCSD Pedestrian (visual anomaly detection)  
- **Benchmarking Standards:** MLPerf Tiny-inspired latency, RAM, and energy profiling  

---

## 🔹 Methodology
1. **Benchmark Framework**  
   - Compared ELM, dCeNN, Tiny CNNs, and neuro-symbolic hybrids.  
   - Evaluated across multi-modal datasets (vibration, aero-engine, healthcare, vision).  

2. **Efficiency Metrics**  
   - Model size (KB/MB), inference latency, RAM usage, CPU cycles, energy per inference.  
   - Deployability tested on Raspberry Pi 4 & Jetson Nano.  

3. **Rule Consistency via ASP**  
   - Encoded domain rules (safety, compliance) in ASP.  
   - Hybridized outputs from dCeNN/ELM with symbolic constraints.  

4. **Comparative Analysis**  
   - Accuracy (F1, AUROC, precision-recall).  
   - Resource trade-offs (accuracy vs latency vs compliance).  

---

## 🔹 Results & Insights
- **ELM + dCeNN**: Excelled in structured time-series (bearing, aero-engine).  
- **Tiny CNNs**: Stronger on visual anomalies (UCSD Pedestrian) under tight footprints.  
- **ASP Integration**: Improved compliance by enforcing symbolic safety rules.  
- **Trade-offs**: Logic-aware hybrids improved interpretability but added slight latency.  

💡 Key outcome: **No single model dominates** — instead, combining **learning + reasoning** yields the best **efficiency + safety balance** for edge robotics.  

---

## 🔹 Challenges & Learnings
- Designing **reproducible benchmarks** across multi-modal datasets.  
- Handling **imbalanced anomaly datasets** (rare failure events).  
- Integrating symbolic reasoning without breaking lightweight constraints.  
- Learned the importance of balancing **accuracy, latency, and explainability**.  

---

## 🔹 Links & Resources
- 📄 [AUTSYS 2025 Extended Abstract](../publications/preprints.md)  
- 📓 [Benchmark Notebooks](../docs/notebooks/edge-forecasting/)  
- 📝 [Review Paper Draft](../docs/manuscripts/review-paper/)  

---

## 🔹 Future Work
- Expand benchmarks with **federated learning + privacy-preserving AD**.  
- Integrate **adversarial robustness testing** for safety-critical robotics.  
- Deploy full pipeline in a **smart factory robotic platform** for predictive maintenance.  
- Extend framework to support **multi-agent robotic swarms** in Industry 4.0.  
