# 📄 Published & Accepted Publications

---

## 1. Enhancing Image Quality via Deep Autoencoder Architectures for Single Image Super-Resolution  
**Authors:** Chamil Oshan Abeysekara, Binura Laksara Widanagama, Witesyavwirwa Vianney Kambale, Mohamed El Bahnasawi, Mahmoud Hamed, Kyandoghere Kyamakya  
**Affiliation:** Institute for Smart Systems Technologies, Universität Klagenfurt, Austria  
**Conference:** *CSCC 2025 – International Conference on Circuits, Systems, Communications and Computers, Italy*  
**Status:** Presented, pending publication  

---

### 🔹 Abstract
This work addresses the fundamental problem of **Single Image Super-Resolution (SISR)**, where the goal is to reconstruct high-resolution (HR) images from low-resolution (LR) inputs. While deep learning has advanced the field, existing approaches often involve computationally heavy models or produce oversmoothed textures.  

We propose a **deep convolutional autoencoder (AESR)** enhanced with **skip connections and residual learning** to balance **high-quality reconstructions with computational efficiency**.  

---

### 🔹 Key Contributions
- **Novel Autoencoder-Based Design**  
  Encoder-decoder network with skip connections and residual enhancements to preserve fine textures and structural detail.  

- **Lightweight Efficiency**  
  Model optimized for CPU-only environments; designed for edge or resource-constrained deployment.  

- **Benchmark Results**  
  - Dataset: DIV2K (2× upscaling).  
  - PSNR: **34.38 dB**  
  - SSIM: **0.9767**  
  - Params: ~915K  
  - Inference: ~220 ms (CPU-only).  

- **Comparison Against Baselines**  
  Outperforms lightweight models such as FSRCNN and classical SRCNN, while approaching or exceeding deeper CNNs like VDSR in both **visual quality** and **quantitative scores**.  

- **Robust Training Performance**  
  Stable convergence within only 10 epochs, showing strong architecture design despite limited training.  

---

### 🔹 Practical Implications
- Suitable for **resource-constrained devices** (embedded systems, surveillance, mobile robotics).  
- Promising for **real-time edge deployment** with GPU/TPU acceleration.  
- Provides a scalable foundation for extensions with perceptual losses, GAN-based refinement, or quantization.  

---

### 🔹 Future Work
- Benchmarking on Set5/Set14 datasets with higher upscaling factors (×3, ×4).  
- Exploring perceptual/adversarial losses for sharper results.  
- Integrating attention mechanisms (SE/CBAM).  
- Model compression for deployment on **Raspberry Pi, mobile GPUs, TPUs**.  

---

🔗 **Colab Implementation:** [AESR on DIV2K](https://bit.ly/AESR-DIV2K-Colab)  
🔗 **Conference Website:** [CSCC 2025](https://cscc.uth.gr/) *(proceedings link will be added once available)*  

