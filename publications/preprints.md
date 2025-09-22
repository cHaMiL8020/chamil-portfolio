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


## 2. A Critical and Comprehensive State of the Art Review on Combining Learning and Reasoning for Edge Anomaly Detection:  
### An Efficient dCeNN, ELM and ASP Approach  

**Author:** Chamil Oshan Abeysekara
**Affiliation:** Institute for Smart Systems Technologies, Universität Klagenfurt, Austria  
**Status:** Draft manuscript (under development for journal submission)  

---

### 🔹 Abstract  
This review surveys the **intersection of learning and reasoning for edge anomaly detection (AD)** in autonomous systems, Industry 4.0, and robotics. Traditional anomaly detection relies heavily on **learning-based approaches** (e.g., CNNs, dCeNN, ELM, TinyML) or **reasoning-based frameworks** (ASP, symbolic AI). However, current works often lack either **efficiency (learning)** or **interpretability/safety (reasoning)**.  

We critically evaluate these paradigms and highlight the need for **hybrid solutions**, specifically the **dCeNN + ELM + ASP nexus**, as a pathway toward efficient, interpretable, and rule-compliant AD at the edge.  

---

### 🔹 Coverage & Structure  
- **Foundations & Concepts**: anomaly detection types, edge constraints, learning vs reasoning paradigms.  
- **Current Landscape**: taxonomy of ML, deep learning, TinyML, and symbolic reasoning methods for edge AD.  
- **Learning-Centric Approaches**: ELM, dCeNN, lightweight CNNs (MobileNet, SqueezeNet, MLPerf Tiny).  
- **Reasoning-Centric Approaches**: ASP, SAT solvers, NeurASP, Semantic Loss, DeepProbLog.  
- **Hybrid Approaches**: integration of logic with deep learning, hybrid clustering + DL, neurosymbolic systems.  
- **The dCeNN + ELM + ASP Nexus**: conceptual framework showing how each paradigm complements the others.  
- **Critical Discussion & Gaps**: lack of unified benchmarks, weak reasoning integration, explainability–efficiency trade-off.  
- **Future Directions**: multi-modal benchmarks, federated AD, adversarial robustness, Industry 4.0 integration.  

---

### 🔹 Contributions  
- Provides the **first structured taxonomy** of learning, reasoning, and hybrid AD approaches tailored for **edge deployment**.  
- Synthesizes literature from 2015–2025 across robotics, CPS, industrial IoT, and healthcare domains.  
- Identifies **research gaps** and proposes a **synergistic dCeNN + ELM + ASP framework**.  
- Serves as a foundation for **future PhD and thesis work** in efficient and interpretable edge AI.  

---

### 🔹 Availability  
- Draft manuscript and detailed outline will be available soon in `docs/manuscripts/review-paper/`.   

