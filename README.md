# 🚦 Traffic Sign Classification using CNN (ResNet, PyTorch)

This project is a deep learning-based traffic sign classifier built using PyTorch and trained on the [GTSRB (German Traffic Sign Recognition Benchmark)](https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) dataset. It leverages a fine-tuned ResNet architecture for robust multi-class classification, achieving high accuracy on both known and unseen data.

---

## 📌 Features

- 📚 Trained on the GTSRB dataset with over 40 traffic sign classes.
- 🧠 Used **ResNet** (Residual Networks) for feature extraction and classification.
- 🎯 Achieved **98% accuracy** on validation set and **100% accuracy** on unknown test cases.
- 🔄 Integrated **learning rate scheduler** with **SGD optimizer** for efficient training.
- 🔍 Data preprocessing and augmentation for generalization.
- 🛠️ Built entirely using **PyTorch**, with additional support from NumPy, Matplotlib, and OpenCV.

---

## 🗂️ Dataset

- **Source**: [GTSRB Dataset](https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset)
- **Classes**: 43 traffic sign categories
- **Format**: RGB images with varying resolutions, normalized and resized to 32x32 for training.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/traffic-sign-classification.git
cd traffic-sign-classification

