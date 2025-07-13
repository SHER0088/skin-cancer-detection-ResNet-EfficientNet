# Skin Cancer Detection using ResNet50 & EfficientNetB0

This project uses deep learning techniques (ResNet50 and EfficientNetB0) to classify skin cancer images into multiple classes using dermoscopic datasets from [Kaggle](https://www.kaggle.com/datasets/drscarlat/melanoma).

## 📁 Files Included

- `Skin_Cancer_ResNet_EfficientNet.ipynb`: Full training and evaluation code.
- `Skin_Cancer_ResNet_EfficientNet.ipynb - Colab(Final).pdf`: PDF export of the notebook.
- `Untitled1.ipynb - Colab.pdf`: Alternate version with slightly different model structure.
- `kaggle.json`: Kaggle API token to fetch the dataset programmatically.

## 🧠 Models Used

- **ResNet50**: Used with fine-tuning and added regularization.
- **EfficientNetB0**: Used with batch normalization, dropout, and Gaussian noise for better generalization.

## 🖼️ Dataset

- [Kaggle - Melanoma Dataset](https://www.kaggle.com/datasets/drscarlat/melanoma)

## 🔧 Setup

1. Install requirements in Colab:
   ```python
   !pip install kaggle
