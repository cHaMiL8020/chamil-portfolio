# 📈 Super-Resolution Autoencoder (2024–2025)

---

## 🔹 Overview
This research project focused on enhancing **Single Image Super-Resolution (SISR)** using lightweight **deep autoencoder architectures**.  
The goal was to achieve **high-quality upscaling** while maintaining **efficiency for CPU-only and edge deployments**.  

The work led to a **conference paper** presented at **CSCC 2025 (Italy)** and demonstrated the viability of autoencoder-based designs for industrial and embedded AI applications.  

---

## 🔹 Context
- **Type:** MSc Research Project  
- **Year:** 2024–2025  
- **Institution:** University of Klagenfurt, Austria  
- **Outcome:** Accepted at CSCC 2025 – *Enhancing Image Quality via Deep Autoencoder Architectures for Single Image Super-Resolution*  

---

## 🔹 Tech Stack
- **Programming:** Python, TensorFlow, Keras  
- **Dataset:** DIV2K (2× upscaling)  
- **Evaluation Metrics:** PSNR, SSIM  
- **Model Components:** Convolutional Autoencoders, Skip Connections, Residual Blocks  
- **Deployment:** CPU-optimized inference, Jupyter Notebooks, Google Colab  

---

## 🔹 Methodology
1. **Problem Definition**  
   - Input: Low-resolution (LR) images  
   - Output: High-resolution (HR) reconstructions  

2. **Model Design**  
   - Deep **convolutional autoencoder** with:  
     - Skip connections to preserve structural details  
     - Residual blocks to improve stability and gradient flow  

3. **Training & Evaluation**  
   - Dataset: DIV2K  
   - Loss function: MSE  
   - Evaluated using **PSNR** and **SSIM**  
   - Compared with **SRCNN, FSRCNN, and VDSR** baselines  

---

## 🔹 Results & Impact
- **PSNR:** 34.38 dB  
- **SSIM:** 0.9767  
- **Model Size:** ~915K parameters  
- **Inference:** ~220 ms on CPU (no GPU)  
- **Comparison:** Outperformed lightweight baselines (SRCNN, FSRCNN) and competitive with deeper VDSR.  

💡 Demonstrated **deployability on resource-constrained devices** (CPUs, edge boards).  

---

## 🔹 Challenges & Learnings
- Balancing **model complexity vs efficiency**.  
- Avoiding oversmoothing while keeping inference lightweight.  
- Learned the trade-offs between **classical CNN methods** and **modern lightweight designs**.  

---

## 🔹 Links & Resources
- 📄 [Published Paper](../publications/published.md)  
- 📓 [Jupyter Notebooks](https://bit.ly/AESR-DIV2K-Colab)  
- 📊 [Results & Plots](../images/super-resolution-results.png)  [In Progress]

---

## 🔹 Future Work
- Explore higher scaling factors (×3, ×4).  
- Integrate perceptual and adversarial losses (GAN-based refinement).  
- Experiment with attention mechanisms (SE/CBAM).  
- Deploy on **Jetson Nano / Raspberry Pi** for real-time robotics and IoT applications.  

