🧠 Alzheimer's Disease Detection from MRI Scans Using Transfer Learning

This project applies deep learning with **transfer learning** to classify brain MRI scans for early detection of Alzheimer’s Disease. Leveraging pre-trained convolutional neural networks (CNNs), the model identifies structural patterns in MRI data to differentiate stages of cognitive decline.

---

## 🎯 Objective

The primary goal is to build an accurate and generalizable image classifier to:
- Detect Alzheimer’s Disease from MRI brain scans
- Use pre-trained models to accelerate training and improve accuracy
- Address class imbalance in medical datasets

---

## 🧠 Methodology

- **Data Source**: MRI scan images categorized into:
  - Non-Demented
  - Very Mild Demented
  - Mild Demented
  - Moderate Demented
- **Transfer Learning**:
  - Models like `VGG16`, `ResNet50`, or `EfficientNet` used as base
  - Top layers fine-tuned for classification
- **Training Strategy**:
  - Early stopping and model checkpoints
  - Stratified train-test split
  - Class weight adjustment for imbalance

---

## 📁 Project Structure

- `Deep Learning Project.ipynb` – Complete notebook: data preprocessing, model building, training, and evaluation
- `README.md` – Project overview and instructions

---

## 🖼️ Key Visualizations

- Class distribution bar chart
- Accuracy and loss curves
- Confusion matrix
- Precision, recall, F1-score reports

---

## 🚀 Getting Started

### Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/alzheimers-mri-transfer-learning.git
cd alzheimers-mri-transfer-learning
