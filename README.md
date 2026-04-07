# Water Body Segmentation using U-Net

## 📌 Overview

This project implements a deep learning-based approach for segmenting water bodies from satellite imagery using a U-Net architecture with a ResNet34 encoder.

## 🚀 Features

* U-Net with pretrained ResNet34 encoder
* BCE + Dice Loss for class imbalance
* Data augmentation (flip, rotation, brightness)
* Evaluation using IoU and Dice Score
* Visualization of predictions

## 📊 Results

* Test IoU: **0.8012**
* Test Dice: **0.8690**

## 📂 Dataset

Kaggle Dataset:
https://www.kaggle.com/datasets/franciscoescobar/satellite-images-of-water-bodies

<img width="1294" height="590" alt="image" src="https://github.com/user-attachments/assets/bf53c20a-305e-4412-8627-2545f7e6ede0" />


## ⚙️ Setup

```bash
pip install -r requirements.txt
```

## ▶️ Run

Open the notebook in Google Colab and run all cells.

## 🧠 Model

* Architecture: U-Net
* Encoder: ResNet34
* Framework: PyTorch

## 📸 Results

<img width="1163" height="2390" alt="image" src="https://github.com/user-attachments/assets/5be1870e-9c87-4642-bb9b-067c6de6e7cf" />

