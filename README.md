# Tomato-Plant-Disease-Detection-and-Classification-Using-Machine-Learning-Techniques
# 🍅 Tomato Leaf Disease Classification using CNN

A Deep Learning based web application that detects and classifies tomato leaf diseases using a Convolutional Neural Network (CNN) with 91.3% accuracy.

---

## 📌 Project Overview

Tomato crops are highly vulnerable to various fungal, bacterial, and viral diseases. Early detection can significantly reduce crop damage and financial loss for farmers.

This project uses a trained CNN model to classify tomato leaf images into 10 different categories and provides prediction confidence via a Streamlit web interface.

---

## 🚀 Features

- Image upload via web interface
- Automatic image preprocessing
- CNN-based disease classification
- 10 disease categories
- Confidence score display
- Clean Streamlit UI

---

## 🧠 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pillow
- Streamlit

---

## 📂 Dataset

Dataset used: PlantVillage Dataset  
Source: https://www.kaggle.com/arjuntejaswi/plant-village

The dataset contains 10 classes:

- Tomato Bacterial Spot
- Tomato Early Blight
- Tomato Late Blight
- Tomato Leaf Mold
- Tomato Septoria Leaf Spot
- Tomato Spider Mites
- Tomato Target Spot
- Tomato Yellow Leaf Curl Virus
- Tomato Mosaic Virus
- Tomato Healthy

---

## 🏗 Model Architecture

- Convolutional Layers
- ReLU Activation
- MaxPooling
- Fully Connected Dense Layers
- Softmax Output Layer

Final Accuracy: **91.30%**

---

## 📸 Application Workflow

1. User uploads tomato leaf image
2. Image resized to 256x256
3. Pixel normalization (0-1 scaling)
4. CNN processes image
5. Disease prediction + confidence displayed

---

## 🖥 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Tomato-Leaf-Disease-Classification-CNN.git
cd Tomato-Leaf-Disease-Classification-CNN
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
streamlit run app.py
```

---

## 📦 Project Structure

```
Tomato-Plant-Disease-Detection-and-Classification-Using-Machine-Learning-Techniques/
│
├── app.py
├── tomatoes.h5
├── Training.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## 📈 Future Improvements

- Deploy on Streamlit Cloud
- Add treatment suggestions for each disease
- Improve accuracy with Transfer Learning
- Add mobile responsiveness
- Add real-time camera capture

---

## 🎯 Real-World Impact

This project can help farmers:
- Detect disease early
- Reduce crop damage
- Improve yield quality
- Reduce financial losses

---

## 👨‍💻 Author

Amaram Vivek
B.Tech Engineering Student  
Machine Learning Enthusiast
