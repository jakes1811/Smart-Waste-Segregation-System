# Smart Waste Segregation System

**AI-Powered Web-Based Waste Classification for Smarter Recycling**

---

## 🚀 Overview

The **Smart Waste Segregation System** is a deep learning–based solution designed to automate the classification of waste into categories such as **Cardboard, E-waste, Glass, Metal, Paper, and Plastic**.

Using a **MobileNetV2** model and real-time webcam detection, this project supports intelligent recycling processes and reduces the need for manual sorting. The system can be used in smart bins, waste management facilities, and educational setups to promote sustainability.

---

## ✨ Features

* 🔍 **Image Classification** – Classifies waste into 6 predefined categories.
* 📷 **Real-Time Detection** – Uses a webcam to perform instant waste type predictions.
* ⚡ **Lightweight Deep Learning Model** – Built using MobileNetV2 for fast inference.
* 🔄 **Custom Training Pipeline** – Includes preprocessing, augmentation, and training scripts.
* 🧪 **Single Image Prediction** – Classify any image via CLI.

---

## 🛠️ Tech Stack

* **Languages**: Python
* **Libraries**: TensorFlow / Keras, OpenCV, NumPy, Matplotlib
* **Model**: MobileNetV2 (Transfer Learning)
* **Interface**: CLI + Webcam Support
* **IDE**: Google Colab / Jupyter Notebook

---

## 🏗️ Getting Started

### Prerequisites

* Python 3.8+
* pip (Python package manager)
* Webcam (for real-time detection)

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/smart-waste-segregation.git
   cd smart-waste-segregation
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **(Optional) Prepare Dataset**

   * Place your dataset under a folder named `waste_dataset/` or modify paths in the training script.

---

## 🧪 Usage

### 1. **Train the Model**

```bash
python train_model.py
```

### 2. **Real-Time Waste Detection (Webcam)**

```bash
python realtime_classification.py
```

### 3. **Classify a Single Image**

```bash
python predict.py --image path/to/image.jpg
```

---

## ♻️ Waste Categories

* Cardboard
* E-waste
* Glass
* Metal
* Paper
* Plastic

---

## 📊 Sample Results

* Training Accuracy: \~92%
* Validation Accuracy: \~89%
* Real-Time FPS: \~15–20 (depending on system)

*(Replace with your actual numbers after testing)*

---

## 📌 Future Enhancements

* Add organic and hazardous waste categories
* Deploy on Raspberry Pi for IoT use
* Create web or mobile interface for wider accessibility
* Smart bin integration

---
