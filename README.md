# Enrico Vezzali
### Senior Machine Learning Engineer & Ph.D. Researcher

I specialize in the research, optimization, and deployment of deep neural networks on resource-constrained embedded platforms. My engineering focus is on maximizing inference efficiency at the edge through **quantization (PTQ/QAT)**, **sparsity**, and **custom SIMD/NEON kernel development**.

<p align="left">
  <a href="https://scholar.google.com/citations?user=4YNp37sAAAAJ&hl=it"><img src="https://img.shields.io/badge/Google_Scholar-Publications-blue?style=flat-square&logo=google-scholar&logoColor=white" alt="Google Scholar"/></a>
  <a href="https://linkedin.com/in/enrico-vezzali"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"/></a>
</p>

---

### ⚙️ Core Technical Stack

**Frameworks & Libraries**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![ONNX](https://img.shields.io/badge/ONNX-005C84?style=flat-square&logo=onnx&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Languages & Hardware Acceleration**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)  ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white) 

**Hardware Targets:** `Qualcomm Snapdragon NPU` | `NVIDIA Jetson` | `Arm Cortex-A` | `RISC-V` | `Intel Cyclone V FPGAs`

---

### 📂 Edge AI & Optimization Output
The repositories below contain my research and industrial architectures:

| Project | Description | Key Metrics / Hardware |
| :--- | :--- | :--- |
| **[VAR-Compressor](https://github.com/Henvezz95/VAR-Compressor)** | Optimization framework for compressing Visual Autoregressive (VAR) generative models. Developed during my visiting period at **ETH Zurich**. | W4A4/INT8 KV-cache quantization on **NVIDIA Jetson Orin**. |
| **[Mosaic-SR](https://github.com/Henvezz95/mosaic-sr)** | Patent-pending super-resolution algorithm using custom multi-step refinement. (IEEE ICIP 2025) | Custom **NEON/AVX kernels** resulting in **+30%** industrial scanner range. |
| **[Web Sentinel Edge](#)** | Real-time industrial object detector integration logic (Proprietary/Closed Source). | **< 10ms** inference via **TFLite** C++ API. |
| **[BarBeR](https://github.com/Henvezz95/BarBeR)** & **[BaFaLo](https://github.com/Henvezz95/BarBeR/tree/main/BaFaLo)** | Open-source CNN architectures and benchmarking repository for 1D/2D barcode localization. (ICPR 2024, Eng. App. of AI) | Optimized execution for **Arm CPU** edge platforms. |
| **[FOOT DaQ](https://github.com/Henvezz95/FOOT-Data-Acquisition-System)** | VHDL implementation of a Data Acquisition System for nuclear physics experiments. | Low-level **FPGA** synthesis. |

> *"Bridging the gap between theoretical deep learning research and hard real-time latency constraints on embedded systems."*
