# 🧠 Brain Tumor MRI Classifier

A deep learning-based desktop application that classifies MRI scans into 44 different categories of brain tumors and conditions using **EfficientNetV2**.

<img width="299" height="397" alt="image" src="https://github.com/user-attachments/assets/da2f82ae-4da5-4b3a-b60f-396dd15562d7" />

![53 _big_gallery](https://github.com/user-attachments/assets/3f085713-f0f5-486a-b101-de7efb67def1)



## 🚀 Features
*   **High Accuracy:** Trained using Transfer Learning on EfficientNetV2B0.
*   **44 Classes:** Identifies specific tumor types (Astrocitoma, Glioblastoma, Meningioma, etc.) and Normal scans across T1, T1C+, and T2 sequences.
*   **User-Friendly GUI:** Simple Tkinter interface for uploading images and viewing real-time predictions.
*   **Fast Inference:** Optimized for CPU usage on local machines.

## 🛠️ Tech Stack
*   **Language:** Python 3.10+
*   **Deep Learning:** TensorFlow / Keras
*   **Image Processing:** OpenCV, Pillow
*   **GUI:** Tkinter
*   **Environment Management:** uv / venv

## 📂 Project Structure
```text







git clone https://github.com
cd Brain-Tumor-MRI-Classifier


2. Create and activate a virtual environment:
#Using standard venv

python -m venv venv
\venv\Scripts\activate  # Windows

Brain_Tumor_MRI_Classifier/
├── data/                   # Dataset organized into 44 subfolders
├── venv/                   # Virtual environment
├── chatbot.py              # Main GUI Application script
├── train.py                # Model training script (optimized for Colab)
├── best_mri_classifier.h5  # Pre-trained model weights
└── requirements.txt        # Project dependencies


