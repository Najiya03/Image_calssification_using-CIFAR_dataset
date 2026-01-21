# Image_calssification_using-CIFAR_dataset

##  Project Overview
This project focuses on **image classification** using the **CIFAR dataset**, a widely used benchmark dataset in computer vision.  
The objective is to classify small color images into predefined categories by applying **Machine Learning / Deep Learning techniques**.

This repository demonstrates the end-to-end workflow of an image classification task including:
- Dataset loading
- Data preprocessing
- Model training
- Model evaluation

---

##  Technologies Used
- **Python**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn / TensorFlow / Keras** (based on notebook implementation)

---

##  Dataset Source
The dataset used in this project is obtained from the official CIFAR dataset website:

- **Dataset Name:** CIFAR (CIFAR-10 / CIFAR-100)
- **Provided by:** Canadian Institute for Advanced Research (CIFAR)
- **Dataset Link:** https://www.cs.toronto.edu/~kriz/cifar.html

### Dataset Description
- Images are **32×32 color images**
- CIFAR-10 contains **10 classes** (e.g., airplane, automobile, bird, cat, etc.)
- CIFAR-100 contains **100 fine-grained classes**
- The dataset is commonly used for benchmarking image classification models

> The dataset is used strictly for educational and academic purposes.

---

##  Workflow
1. Import required libraries  
2. Load the CIFAR dataset  
3. Explore and visualize image samples  
4. Preprocess image data (normalization, reshaping, etc.)  
5. Split data into training and testing sets  
6. Train classification model   
7. Evaluate model performance  
8. Predict class labels for unseen images  

---

##  Model Details
- Image features are extracted directly from pixel values
- CNN model is trained on labeled image data
- Model performance is evaluated on test data


---

##  Model Evaluation
The model is evaluated using:
- **Accuracy**
- **Loss metrics**
- Visual comparison of predicted vs actual labels

---
