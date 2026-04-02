# COREPULSE 12D: AI-Powered ECG Analysis System

**COREPULSE 12D** is a clinical decision support system developed for the **2026 Teknofest Health in AI Competition (High School Level)**. It utilizes deep learning to classify 12-lead ECG signals into three primary cardiac categories.

## 🚀 Key Features
- **1D-SE-ResNet Architecture:** A robust 9-million parameter model with Squeeze-and-Excitation blocks.
- **Explainable AI (XAI):** Integrated **Grad-CAM** heatmaps to highlight segments influencing the model's decision.
- **Real-time Inference:** Interactive dashboard built with **Streamlit** for instant diagnosis.

## 📊 Classification Scheme
The model is trained to detect:
1. **Arrhythmias:** AFib, AFL, SVT, Bradycardia, etc.
2. **Conduction Blocks:** AV Blocks, Bundle Branch Blocks.
3. **Normal ECG:** Normal Sinus Rhythm.

## 🛠️ Technical Stack
- **Language:** Python 3.11+
- **Framework:** PyTorch 2.x
- **Visualization:** Plotly, Matplotlib
- **Datasets:** PTB-XL, MIT-BIH, Kaggle ECG Heartbeat Categorization.

## 📦 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)[your-username]/corepulse-12d-ecg-ai.git
