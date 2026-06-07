# ⚙️ Fitra Machine Learning System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-orange.svg" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Gradio-UI-ff5500.svg" alt="Gradio">
  <img src="https://img.shields.io/badge/Whisper-AI-green.svg" alt="Whisper">
</p>

## 📌 Project Mission
**Fitra Machine Learning System** is an AI-powered solution explicitly designed to **protect children from sexually deviant content on YouTube**. By leveraging advanced Machine Learning (ML) and Natural Language Processing (NLP), the system scans video metadata and audio transcripts to detect inappropriate agendas, ensuring a safe and clean digital environment for kids.

---

## 🚀 How It Works
The system analyzes YouTube videos through a simple 3-step pipeline:
1. **Audio & Text Extraction:** Downloads the video's audio and uses **OpenAI Whisper** to transcribe the speech into text (NLP).
2. **AI Analysis:** Processes the text and metadata using a hybrid **CNN-LSTM** deep learning model.
3. **Classification:** Instantly flags whether the content is safe or unsafe.

---

## 🛠️ Technologies Used
* **AI & Deep Learning:** Python, TensorFlow / Keras, Scikit-learn
* **Natural Language Processing (NLP):** FastText (Gensim), OpenAI Whisper
* **Data & Automation:** yt-dlp, NumPy, Pandas
* **Interface:** Gradio

---

## 🎯 Classification Goals
* **Safe (غير شاذ):** Clean, wholesome content perfectly suitable for children.
* **Unsafe (شاذ):** Contains sexually deviant themes or inappropriate agendas targeting kids.

---

## 💻 How to Run the Project


Follow these steps to set up and launch the web interface on your Google Colab:
Follow these steps to set up and launch the web interface on Google Colab:

1. Upload the project files to your Colab environment (or mount Google Drive) so that `app.py` and all required files are available.

2. Download or place the required model files in your working directory:
- CNN_LSTM_reinforced.h5
- fasttext_model.model

3. Make sure the model paths inside the code are correct and point to the actual location of the files in Colab (for example `/content/` or your Google Drive path).

4. Run the project
