# 🌾 Crop Disease Classification Using CNN & Transfer Learning  
### **WorldQuant University – Deep Learning for Computer Vision Lab (Project 2)**

This repository contains my second project for the **Deep Learning for Computer Vision Lab** at **WorldQuant University**. The project focuses on building and optimizing convolutional neural networks (CNNs) to classify crop disease images collected from agricultural fields in Uganda. It demonstrates a full computer vision workflow including dataset analysis, baseline modeling, transfer learning, performance evaluation, and training optimization using callbacks.

---

## ⭐ Project Summary

This project aims to classify crop leaf images into **five disease classes** using deep learning. It combines custom CNN architectures and state-of-the-art transfer learning models to achieve high accuracy and robust generalization. Techniques such as data augmentation, cross-validation, and callbacks are used to improve training stability and performance.

---

## 🎯 Project Objectives

By the end of this project, I successfully completed:

- 📊 Exploring and analyzing a real-world crop disease image dataset  
- 🧠 Building and training a baseline CNN from scratch  
- 🔄 Applying **Transfer Learning** (EfficientNet, MobileNetV2, or ResNet50)  
- 🛑 Identifying and mitigating **overfitting** using dropout and regularization  
- ♻️ Applying **k-fold cross-validation** for robust performance evaluation  
- ⚙️ Using key Pytorch Callbacks:
  - **EarlyStopping**  
  - **ModelCheckpoint**  
  - **ReduceLROnPlateau**  
  - **LearningRateScheduler**

---

## 🗂️ Dataset Description

The dataset contains labeled crop leaf images from Uganda representing **five categories**. It includes:

- healthy
- green mottle virus (CGM)
- bacterial blight (CBB)
- brown streak disease (CBSD)
- mosaic disease (CMD)  

> *Note: Due to licensing restrictions, the dataset is not stored in this repository. Instructions for downloading/loading the dataset are included in the notebooks.*

---

## 🧰 Technologies & Libraries Used

- **Python 3.x**
- **Pytorch**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **scikit-learn**
- **Jupyter Notebook**
- **CNNs + Transfer Learning Models**

---

## 🧠 Modeling Approach

### **1. Baseline CNN**
- Custom convolutional architecture  
- Trained from scratch  
- Served as a performance benchmark  

### **2. Transfer Learning**
- Fine-tuned pre-trained models (e.g., EfficientNet, MobileNetV2)  
- Added custom classification head  
- Achieved significant accuracy improvement  

### **3. Callbacks for Training Optimization**
- **EarlyStopping** to prevent overfitting  
- **ModelCheckpoint** to save the best-performing model  
- **ReduceLROnPlateau** for adaptive learning rate control  
- **LearningRateScheduler** for step-based schedule  

### **4. K-Fold Cross-Validation**
- Evaluated model performance across multiple folds  
- Ensured stability and reliable metrics  

---

## 📈 Evaluation Metrics

The model was evaluated using:

- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Training/Validation learning curves  
- Cross-validation fold accuracy  
- Test accuracy on unseen images  

---

## 👤 Author

- Yusuf Hassan
- Machine Learning Intern | Data Scientist
- Aspiring AI Engineer & Researcher

