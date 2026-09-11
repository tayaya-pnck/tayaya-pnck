# Hi there, I'm Athaya Abdan Hanif 👋

### 🧠 AI/ML Engineer | Biomedical AI Researcher

I build robust machine learning architectures that extract precise meaning from messy, real-world data. My work focuses on bridging the gap between traditional predictive algorithms (CNNs, BiGRUs, YOLO) and modern Generative AI (LLMs, RAG) to create scalable, end-to-end intelligent systems. 

Whether it is multi-stage denoising for clinical audio or injecting real-time diagnostic probabilities into an LLM's active memory buffer, I engineer AI that is efficient, mathematically grounded, and deployable.

📫 **Reach me at:** [athayahanif.18@gmail.com](mailto:athayahanif.18@gmail.com) | [LinkedIn Profile](https://linkedin.com/in/athayahanif) 

---

## 🛠️ Technical Arsenal

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Deep Learning & ML** | PyTorch, TensorFlow, Scikit-Learn, YOLOv8, CNNs, RNNs (BiGRU, LSTM) |
| **Generative AI & LLMOps** | RAG Pipelines, ChromaDB (Vector Stores), Prompt Engineering |
| **Signal & Audio Processing** | MFCC Extraction, Wavelet Transforms, Librosa, Butterworth Filters, EMD |
| **MLOps & Deployment** | Docker (Docker Compose), Streamlit, Git, PostgreSQL |
| **Languages** | Python (Advanced), SQL, Java |

---

## 🚀 Featured Projects

### 🏥 [End-to-End Diabetes AI Chatbot & Prediction Engine](Link-To-Your-Repo)
*Bridging predictive ML with Generative AI via Retrieval-Augmented Generation (RAG).*
* **The Architecture:** Designed a full-stack clinical application where user parameters pass through a predictive ML classifier, dynamically injecting the resulting diagnostic probabilities into an LLM's active memory buffer.
* **Medical Grounding:** Integrated **ChromaDB** to retrieve verified medical literature, allowing the agent to synthesize statistical risk metrics with contextual facts.
* **Deployment:** Containerized the entire pipeline via **Docker Compose** and hosted the UI via **Streamlit**.
> **Tech Stack:** `Python` `LLMs` `ChromaDB (RAG)` `Scikit-Learn` `Docker` `Streamlit`

### 🫁 [Clinical Respiratory Disease Audio Classification](Link-To-Your-Repo)
*Undergraduate Thesis: Highly efficient deep learning for noisy clinical environments.*
* **The Pipeline:** Engineered a multi-stage denoising pipeline for 6,896 raw clinical audio files using Butterworth filters and Empirical Mode Decomposition (EMD) to isolate 20-2000 Hz physiological frequencies.
* **The Model:** Built a custom hybrid **CNN-BiGRU** network to extract spatial features from MFCC tensors while modeling long-range temporal dependencies.
* **The Impact:** Achieved a **92.5% macro F1-score** on highly imbalanced data (via custom time-stretching/pitch-shifting oversampling scripts) while reducing computational complexity by **46%** compared to baseline architectures.
> **Tech Stack:** `PyTorch/TensorFlow` `CNN-BiGRU` `Librosa (MFCC)` `Signal Processing`

### 🚘 [Real-Time Pothole Detection System](Link-To-Your-Repo)
*Low-latency computer vision for automated public infrastructure maintenance.*
* **The System:** Developed an automated CV pipeline utilizing **YOLOv8n** to identify and track road degradation from high-speed dashcam footage.
* **The Optimization:** Implemented Automatic Mixed Precision (AMP) and the AdamW optimizer to maximize inference efficiency.
* **The Impact:** Increased real-time video processing speeds by **40%**, ensuring seamless, low-latency bounding box rendering.
> **Tech Stack:** `Computer Vision` `YOLOv8n` `AMP` `AdamW`

### 🗣️ [Speech Emotion Recognition (SER) System](Link-To-Your-Repo)
*Classifying human emotional states from complex vocal patterns.*
* **The Engine:** Built a deep learning classification system using **CNNs** trained on 7,442 raw audio clips from the CREMA-D dataset.
* **Audio Processing:** Authored Python scripts to dynamically convert raw waveforms into spectrograms and extract spatial Mel-Frequency Cepstral Coefficients (MFCCs).
* **Generalization:** Mitigated severe target class imbalance via automated dynamic noise injection and pitch shifting pipelines.
> **Tech Stack:** `Python` `CNNs` `Audio Data Augmentation` `MFCCs`

---
*Looking to collaborate on robust AI solutions, GenAI applications, and biomedical ML research.*
