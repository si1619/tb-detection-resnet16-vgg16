# 🧠 Tuberculosis Prediction using ResNet16 and VGG16

This project focuses on early detection of Tuberculosis (TB) using deep learning models — **ResNet16** and **VGG16** — applied to **Chest X-Ray (CXR)** images. The models aim to classify whether a CXR scan indicates TB or not.

---

## 📂 Project Structure

- `tb_prediction_resnet16.ipynb` – TB prediction using ResNet16 architecture  
- `tb_prediction_vgg16.ipynb` – TB prediction using VGG16 architecture  
- `/data/` – Directory containing CXR images (not included here due to size)
- `README.md` – Project overview and instructions

---

## 📌 Objectives

- Build CNN models (ResNet16 & VGG16) for binary classification (TB / Normal)
- Use transfer learning and image preprocessing techniques
- Evaluate model performance using accuracy, confusion matrix, and classification report

---

## 🛠️ Technologies Used

- Python 🐍  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📊 Dataset

We use a publicly available **Chest X-Ray (CXR)** dataset that contains labeled TB and normal chest scans.  
Example sources:
- [TB CXR dataset - Kaggle](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)
- [NIH Chest X-rays](https://nihcc.app.box.com/v/ChestXray-NIHCC)

> *(Note: You must manually download the dataset and place it in the `/data/` folder.)*

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/tb-detection-resnet16-vgg16.git
   cd tb-detection-resnet16-vgg16
