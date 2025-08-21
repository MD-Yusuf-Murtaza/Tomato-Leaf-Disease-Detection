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

* **Training Accuracy:** \~98%
* **Validation Accuracy:** \~96%
* **Loss & Accuracy Curves:** Included in the notebook.
* **Sample Prediction Visualization:** Demonstrates correct classification of tomato leaf diseases.

---

