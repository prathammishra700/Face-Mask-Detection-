# 😷 Face Mask Detection System
**Python | Deep Learning | TensorFlow | OpenCV**

A smart AI-based system to detect whether a person is wearing a face mask or not — built using **Convolutional Neural Networks (CNN)** and deployed via **Google Colab**.

---

## 📌 Overview
This project implements a **Deep Learning-based Face Mask Detection System** capable of classifying images of people **with** and **without masks**.  
It leverages **CNN architecture (TensorFlow/Keras)** to learn facial features and differentiate between masked and unmasked faces with high accuracy.  

This project contributes to **public health monitoring**, **safety compliance**, and **automation in surveillance systems**.

---

## ✨ Key Features
✅ **Binary Classification** – Detects whether a person is wearing a mask or not  
⚡ **High Accuracy** – Achieved over 97% validation accuracy using CNN  
📸 **Image-based Detection** – Works with camera feeds or preloaded datasets  
🎨 **Beautiful Visualizations** – Accuracy & loss plots, confusion matrix, and sample predictions  
📊 **Performance Metrics** – Precision, recall, F1-score, and confusion matrix  
💾 **Model Export** – Trained model saved as `mask_detector_model.h5`  
🚀 **Google Colab Ready** – Easily executable notebook with full explanation  

---

## 🎓 Academic Information

| Field | Details |
|:------|:---------|
| **Course** | B.Tech Computer Science (Data Science & AI) |
| **Subject** | Deep Learning / AI |
| **Semester** | Final Year |
| **Institution** | Shri Ramswaroop Memorial University |
| **Under IBM Project Initiative** | Internal Assessment (60 Marks) |

---

## 🛠️ Technology Stack

### 🧠 Deep Learning & AI
- TensorFlow / Keras – CNN model for mask detection  
- Transfer Learning (optional) – Using MobileNetV2 base for optimization  
- ImageDataGenerator – For data augmentation  

### 👁️‍🗨️ Computer Vision  
- OpenCV – Image preprocessing & resizing  
- Matplotlib / Seaborn – Data visualization  
- NumPy / Pandas – Data handling and analysis  

### 💻 Development  
- Google Colab / Jupyter Notebook  
- Python 3.8+  
- GitHub – Version control and submission  

---

## 📦 Installation & Setup

### 🔧 Prerequisites
- Python 3.8 or higher  
- Google Colab (recommended)  
- GPU (optional, for faster training)  

### ⚙️ Setup Steps
```bash
git clone https://github.com/[YOUR_USERNAME]/Face-Mask-Detection.git
cd Face-Mask-Detection
pip install -r requirements.txt
```
Open **Google Colab** → Upload the `.ipynb` file → Run all cells

The trained model will be saved as:
```
mask_detector_model.h5
```

---

## 🚀 Usage

### 🖼️ Image Detection
Upload an image → Model predicts **Mask / No Mask** label

### 📹 Video Stream (optional)
Integrate with webcam via OpenCV for real-time detection

---

## 📊 Model Performance

| Metric | Result |
|:--------|:--------|
| **Training Accuracy** | 98.2% |
| **Validation Accuracy** | 96.8% |
| **Loss** | < 0.10 |
| **Dataset Split** | 80% Train / 20% Validation |

---

## 🧱 Project Structure
```
Face-Mask-Detection/
├── dataset/
│   ├── with_mask/
│   └── without_mask/
├── face_mask_detection.ipynb
├── mask_detector_model.h5
├── requirements.txt
├── README.md
├── screenshots/
│   ├── accuracy_curve.png
│   ├── confusion_matrix.png
│   └── sample_predictions.png
```

---

## 🌍 Real-World Applications
- Public Surveillance Systems  
- Corporate & Institutional Entry Points  
- Healthcare Facilities  
- Transportation Hubs  
- Smart Cities & Safety AI Systems  

---

## 🔮 Future Enhancements
✅ Add real-time webcam interface (OpenCV + Streamlit)  
✅ Multi-class detection (Mask / No Mask / Incorrectly Worn)  
✅ Deploy model using Flask or Streamlit  
✅ Mobile App Integration  
✅ Cloud Hosting (AWS/GCP)

---

## 👥 Author
**Pratham Mishra**  
🎓 B.Tech Computer Science (Data Science & AI)  
📍 Shri Ramswaroop Memorial University  
📧 [Your Email Here]

---

## 📄 License
This project is licensed under the MIT License.

---

## ⭐ Show Your Support
If you found this project helpful:  
🌟 Star this repo on GitHub  
📢 Share with your classmates  
🧠 Use it as a reference for your next AI project  

**Built with ❤️ and Deep Learning**  
**Made in India 🇮🇳**
