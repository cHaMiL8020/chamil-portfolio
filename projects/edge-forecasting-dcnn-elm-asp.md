# ⚡ Edge Forecasting with dCeNN + ELM + ASP (2025–2026)

---

## 🔹 Overview
This project investigates **lightweight forecasting and anomaly detection** for **edge devices** used in autonomous robots and Industry 4.0 systems.  
The approach integrates:  
- **Discrete Cellular Neural Networks (dCeNN)** for spatiotemporal feature extraction  
- **Extreme Learning Machines (ELM)** for fast, single-pass classification  
- **Answer Set Programming (ASP)** for rule consistency and symbolic reasoning  

The combination delivers **efficient, interpretable, and rule-compliant anomaly detection** directly at the edge — without reliance on cloud computing.  

---

## 🔹 Context
- **Type:** MSc Thesis + Research Project  
- **Year:** 2025–2026  
- **Institution:** University of Klagenfurt, Austria  
- **Outcomes:**  
  - Extended abstract (*Comparative Evaluation of Lightweight Anomaly Detection Techniques Across Diverse Models and Multi-Modal Datasets for Autonomous Robotic Edge Platforms*).  
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
- 📄 [Benchnark 2025 Extended Abstract](../publications/preprints.md)  
- 📓 [Benchmark Notebooks](../docs/notebooks/edge-forecasting/)   [In Progress]
- 📝 [Review Paper Draft](../docs/manuscripts/review-paper/)   [In Progress]

---

## 🔹 Future Work
- Expand benchmarks with **federated learning + privacy-preserving AD**.  
- Integrate **adversarial robustness testing** for safety-critical robotics.  
- Deploy full pipeline in a **smart factory robotic platform** for predictive maintenance.  
- Extend framework to support **multi-agent robotic swarms** in Industry 4.0.  

---

## 🔹 Alignment with Industry 5.0
While rooted in **Industry 4.0 applications** (smart factories, predictive maintenance, robotics), this research also supports the **Industry 5.0 vision**:  
- **Human-centric AI** – explainable results through ASP reasoning.  
- **Sustainability** – lightweight, energy-efficient deployment on edge devices.  
- **Resilience** – hybrid learning + reasoning improves robustness against faults.  

This dual perspective ensures the framework remains relevant for both **current Industry 4.0 deployments** and the **emerging Industry 5.0 paradigm**.  
