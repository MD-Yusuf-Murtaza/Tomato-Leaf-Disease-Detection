# Tomato Leaf Disease Detection with ResNet50 & Early Stopping

## Overview

This project uses **Deep Learning** to detect different types of tomato leaf diseases with high accuracy.
It leverages a **pre-trained ResNet50** model, fine-tuned on the **PlantVillage dataset**, and incorporates **Early Stopping** to prevent overfitting and achieve better generalization.

---

## Key Features

* **Transfer Learning:** Utilizes ResNet50 for feature extraction and classification.
* **Early Stopping:** Monitors validation performance to halt training when no improvement is observed.
* **Data Augmentation:** Improves model robustness through transformations like rotation, flipping, and normalization.
* **High Accuracy:** Achieved **98% accuracy** on the validation set.
* **Visualizations:** Includes training metrics and sample predictions.

---

## Dataset

* **Source:** [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
* **Classes:** Multiple disease categories + healthy leaves.
* **Preprocessing:**


  * Data cleaning and verification
  * Splitting into **Train (80%)**, **Validation (20%)**, and **Test (5 images of each class)**
  * Normalization to ResNet50 standards

---

## Results

* **Training Accuracy:** \~99%
* **Validation Accuracy:** \~96%
* **Tesing Accuracy:** \~98%
* **Confusion Matrix of Test data prediction**<img width="810" height="753" alt="931ada48-d6d4-4d9f-87c4-5eda8c30677e" src="https://github.com/user-attachments/assets/857962d2-a838-433d-b574-12a4c045d12c" />
* **Loss & Accuracy Curves:** Included in the notebook.
* **Sample Prediction Visualization:** Demonstrates correct classification of tomato leaf diseases.

---

