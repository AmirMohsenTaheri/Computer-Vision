# 🧠 Intel Image Classification using VGG16 (Transfer Learning)

This repository contains an **Image Classification** project trained on the **Intel Image Classification** dataset from Kaggle.  
The project uses **Transfer Learning** with the **VGG16** model to achieve high accuracy with limited training data and reduced training time.

---

## 📂 Dataset

Dataset used: **Intel Image Classification Dataset**()

It includes **6 classes**:

- Buildings  
- Forest  
- Glacier  
- Mountain  
- Sea  
- Street  

Dataset link:  
🔗[dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification/data)

Dataset structure:
* seg_train
    - buildings
    - forest
    - glacier
    - mountain
    - sea
    - street
* seg_test
    - buildings
    - forest
    - glacier
    - mountain
    - sea
    - street
* seg_pred

## 🏗️ Model Architecture
### This project uses **VGG16** as the base model:
- Pretrained on ImageNet  
- Convolutional layers **frozen** (Feature Extractor phase)  
- Custom classification head added  
- Trained for 6 categories

### Techniques used:
  - Data Augmentation
  - tf.data  
  - EarlyStopping  
  - ReduceLROnPlateau

## 📊 Results

### Accuracy: 
- **Train Accuracy:** ~98%  
- **Validation Accuracy:** ~98%   
- **Test Accuracy:** ~92%

### Loss:
- **Train Loss:** ~0.085 
- **Validation Loss:** ~0.05 
- **Test Loss:** ~0.2

## 🧪 Prediction

At the end of the notebook, several custom images are tested.  
Output includes:

- Image  
- Predicted label  

## ✅ You can find me at:
1. [![Linkedin](https://i.sstatic.net/gVE0j.png) LinkedIn](https://www.linkedin.com/in/amirmohsen-taheri)
2. [![GitHub](https://i.sstatic.net/tskMh.png) GitHub](https://github.com/AmirMohsenTaheri)
4. **Gmail** : **amirmohsentaheri.k@gmail.com**
