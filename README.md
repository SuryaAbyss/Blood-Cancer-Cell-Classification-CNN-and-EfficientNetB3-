# Blood Cell Cancer Classification using CNN and EfficientNetB3

This project aims to classify blood cell images to detect cancerous cells using **Convolutional Neural Networks (CNN)** and **EfficientNetB3** architecture.

---

## 📑 Table of Contents
- [Overview](#overview)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Notebook Structure](#notebook-structure)  
  - [Import Necessary Libraries](#import-necessary-libraries)  
  - [Reading the Data](#reading-the-data)  
  - [Explore the Data](#explore-the-data)  
  - [Data Preprocessing](#data-preprocessing)  
  - [Building the Model](#building-the-model)  
  - [Training the Model](#training-the-model)  
  - [Evaluating the Model](#evaluating-the-model)  
  - [Using EfficientNetB3](#using-efficientnetb3)  
- [Conclusion](#conclusion)  
- [Results](#results)  

---

## 🔍 Overview
This project leverages deep learning techniques to classify blood cell images into **cancerous** and **non-cancerous** categories.  

- A **basic CNN model** is implemented initially.  
- Later, the model is enhanced using **EfficientNetB3** for improved accuracy.  

---

## 📂 Dataset
- The dataset is sourced from **Kaggle** and contains images of various blood cell types.  
- Images are organized into separate folders for each cell type.  

---

## ⚙️ Installation
To run the notebook, ensure the following libraries are installed:  

- TensorFlow  
- Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- OpenCV  
- Pillow (PIL)  

Install dependencies using:  
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn opencv-python pillow
