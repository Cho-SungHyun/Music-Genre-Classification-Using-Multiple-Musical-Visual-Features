# Music Genre Classification Using Multiple Musical Visual Features

This repository contains the implementation and experimental results for the research presented at the **IEIE (The Institute of Electronics and Information Engineers) Summer Conference 2022**.

### 🎼 Research Focus: Multi-Feature Deep Learning
The study explores a **multi-input CNN architecture** based on **DenseNet** to improve music genre classification. By leveraging various spectral representations simultaneously, the model captures a more holistic view of acoustic patterns compared to single-feature models.

### 🛠 Technical Approach
- **Multi-Input DenseNet:** Designed a custom DenseNet-based framework in **PyTorch** that processes three distinct musical features in parallel:
  - **STFT** (Short-Time Fourier Transform)
  - **Mel-Spectrogram**
  - **MFCC** (Mel-Frequency Cepstral Coefficients)
- **Advanced Data Engineering (Sliding Window):** To overcome the "small data" challenge, I implemented a data augmentation strategy by slicing 30-second audio clips into 10-second segments with a 5-second overlap, effectively increasing the training sample size and model robustness.

### 📈 Key Results
- The proposed model outperformed baseline architectures in **5 out of 7 datasets**, proving that integrating multiple spectral features significantly enhances classification accuracy.

### 🔗 Publication Information
- **Journal:** Proceedings of IEIE Summer Conference 2022
- **Conference:** The Institute of Electronics and Information Engineers
- **Published:** June 2022

---
### 💡 Relevance to Applied ML & Data Science:
This project highlights my ability to **architect complex neural networks** and handle **data scarcity** through creative engineering. My experience with **PyTorch** and **Sliding Window augmentation** is directly applicable to building robust time-series or sequence models in high-stakes production environments.
