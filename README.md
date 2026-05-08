# 🚗 Vehicle Damage Detection App

An AI-powered web application that detects and classifies vehicle damage using Deep Learning and Transfer Learning techniques.

This application allows users to upload a locally stored image of a vehicle, and the model predicts the type of damage present in the car image through an interactive Streamlit interface.

---

# ✨ Features

- Upload car images through an easy-to-use web interface
- Predict vehicle damage in real time using AI
- Built using Deep Learning and Transfer Learning techniques
- Supports multiple front and rear damage categories
- Lightweight and user-friendly Streamlit application
- Quick and efficient image classification system

---

# 📷 How It Works

1. Download or capture a vehicle image
2. Upload the image through the application
3. The AI model analyzes the image
4. The predicted damage category is displayed instantly

---

# 📸 Application Demo

![Application Screenshot](img.png)

---

# 🧠 Model Overview

This project uses **ResNet50** with Transfer Learning for vehicle damage classification.

## 📌 Supported Classes

- Front Normal
- Front Crushed
- Front Breakage
- Rear Normal
- Rear Crushed
- Rear Breakage

---

# 📊 Training Details

- Dataset Size: ~1700 images
- Model Used: ResNet50
- Framework: PyTorch
- Validation Accuracy: ~76%
- Image-based classification approach

The model was mainly trained on third-quarter front and rear-side vehicle images to improve damage recognition performance.

---

# 🛠️ Tech Stack

- Python
- PyTorch
- Streamlit
- torchvision
- PIL

---

# ⚙️ Installation

## Clone the repository

```bash
git clone <your-repository-link>
cd vehicle-damage-detection
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run the application

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```bash
vehicle-damage-detection/
│
├── app.py
├── model_helper.py
├── requirements.txt
├── saved_model/
├── images/
└── README.md
```

---

# 🚀 Future Improvements

- Add side-view damage detection
- Improve accuracy with larger datasets
- Deploy on cloud platforms
- Add damage severity estimation
- Generate repair cost predictions

---

# 📌 Note

This project was built for learning and educational purposes in the field of Computer Vision and Deep Learning.