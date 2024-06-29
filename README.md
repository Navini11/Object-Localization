# 📦 Object Localization with PyTorch

This project demonstrates object localization using deep learning with PyTorch. The model predicts bounding boxes around objects within images, making it ideal for applications in computer vision and robotics.

## 🔍 Overview

![Screenshot 2024-06-30 011439](https://github.com/Navini11/Object-Localization/assets/123384639/31f84d18-afc7-4d9f-a2b7-c53b6e64d8cc)

- **Task**: Object localization on images.
- **Dataset**: Custom dataset with bounding box annotations.
- **Model**: Fine-tuned EfficientNet from TIMM.
- **Augmentations**: Applied using Albumentations.

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/object-localization.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 📁 Dataset

Download and extract the dataset:
```bash
git clone https://github.com/parth1620/object-localization-dataset.git
```

## 🚀 Getting Started

1. **Data Preparation**: Load and visualize the dataset.
2. **Augmentations**: Apply transformations to enhance the dataset.
3. **Model Training**: Train the EfficientNet model to predict bounding boxes.
4. **Inference**: Test the model on validation data and visualize predictions.

## 📊 Results

- **Training Loss**: [Include metrics]
- **Validation Loss**: [Include metrics]

## 🎯 Usage

Run the training script:
```bash
python train.py
```

Run inference on sample images:
```bash
python inference.py
```

## 🔧 Features

- Custom Dataset Class
- Data Augmentation
- EfficientNet Backbone
- MSE Loss for Bounding Box Regression

## 🧰 Tools & Libraries

- PyTorch
- TIMM (PyTorch Image Models)
- OpenCV
- Albumentations

## 📜 License

This project is licensed under the MIT License.
This is under the guided project done in coursera course, "deep-learning-with-pytorch--object-localization"
