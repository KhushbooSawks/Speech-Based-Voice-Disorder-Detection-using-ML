# 🎙️ Speech-Based Gender & Voice Disorder Detection using Machine Learning

## 🚀 Overview

This project presents an end-to-end **speech analysis system** for detecting **gender** and **voice disorders** (Cyst, Polyp, Laryngitis) using machine learning and signal processing techniques.

The system analyzes voice recordings and extracts meaningful features to identify whether a voice is **healthy or affected by a disorder**, providing a **non-invasive and intelligent diagnostic approach**.

---

## 🎯 Key Features

* 👤 **Gender Classification** (Male vs Female)
* 🧬 **Voice Disorder Detection**

  * Cyst vs Healthy
  * Polyp vs Healthy
  * Laryngitis vs Healthy
* 📊 **Multi-feature Extraction**

  * MFCC (Mel-Frequency Cepstral Coefficients)
  * Acoustic Features (Jitter, Shimmer, HNR, etc.)
  * Time-Frequency Features (Spectrograms)
* 🤖 **Machine Learning & Deep Learning Models**

  * Support Vector Machine (SVM)
  * Convolutional Neural Network (CNN)

---

## 🧠 Methodology

1. 🎧 **Data Collection**

   * Voice samples collected in controlled environments
   * Healthy and disorder datasets (Cyst, Polyp, Laryngitis)

2. ⚙️ **Preprocessing**

   * Noise removal
   * Silence trimming
   * Standardization of audio

3. 📈 **Feature Extraction**

   * MFCC (13 coefficients)
   * Acoustic features (12 features)
   * Time-frequency features (17 features)

4. 🤖 **Model Training**

   * SVM for numerical features
   * CNN for spectrogram-based classification

5. 📊 **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix

---

## 📊 Results

| Task                  | Model      | Accuracy |
| --------------------- | ---------- | -------- |
| Gender Classification | SVM (Best) | ~90%     |
| Laryngitis Detection  | SVM        | ~86%     |
| Polyp Detection       | SVM        | ~94%     |
| Cyst Detection        | SVM        | ~95%     |

👉 Models show strong performance in detecting vocal disorders using speech signals.

---

## 🛠️ Tech Stack

**Programming Languages:**

* Python

**Libraries & Tools:**

* Librosa
* Scikit-learn
* TensorFlow / Keras
* NumPy, Pandas, Matplotlib

**Concepts Used:**

* Digital Signal Processing (DSP)
* Feature Engineering
* Machine Learning
* Deep Learning

---

## 📁 Project Structure

```
speech-based-disease-detection-ml/
│── gender-classification.ipynb
│── cyst-detection.ipynb
│── polyp-detection.ipynb
│── laryngitis-detection.ipynb
│── README.md
```

---

## 💡 Applications

* Early detection of vocal disorders
* Healthcare support systems
* Voice-based diagnostics
* Speaker analysis & biometrics

---

## 🔮 Future Scope

* Real-time voice detection system
* Mobile/Web-based healthcare application
* Integration with IoT devices
* Larger dataset for improved accuracy

---

## 👩‍💻 Author

**Khushboo Kumari**
Electronics & Communication Engineering
AI/ML | Speech Processing | Embedded Systems

📧 Email: [khushboosawks@gmail.com](mailto:khushboosawks@gmail.com)

---

💬 *“Transforming voice signals into intelligent healthcare insights using AI.”*
