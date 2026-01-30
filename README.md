 # 🐱🐶 Image Classification Project

### Cat vs Dog Classification using Transfer Learning & Explainable AI

This project implements a **binary image classification system** to distinguish between **cats and dogs** using **Transfer Learning** with **MobileNetV2**.
To improve model transparency and interpretability, **Explainable AI (Grad-CAM)** is integrated to visualize the regions of an image that influence predictions.

The project is developed using **TensorFlow** and **Keras**, with a focus on clean structure, reproducibility, and educational value.

---

## 📌 Project Overview

* Binary image classification (Cat vs Dog)
* Pretrained **MobileNetV2** used as the feature extractor
* Fine-tuned classification head for prediction
* Confidence score generated for each prediction
* **Grad-CAM** applied for explainable visual interpretation
* Designed for learning, internship tasks, and academic demonstration

---

## ✨ Key Features

* Cat vs Dog image classification
* Transfer Learning with **MobileNetV2**
* Confidence-based predictions
* Explainable AI using **Grad-CAM**
* Visualization outputs:

  * Grayscale attention map
  * Colored Grad-CAM heatmap
  * Heatmap overlay on original image
* Clean, modular, and reproducible project structure

---

## 🧠 Model Architecture

* **Base Model:** MobileNetV2 (pretrained on ImageNet)
* **Pooling Layer:** Global Average Pooling
* **Classifier:** Fully Connected Dense Layer (Binary Output)
* **Framework:** TensorFlow & Keras

---

## 📁 Project Structure

The dataset and project folder structure is documented separately to keep the repository lightweight and reproducible.

📄 **Project Structure Documentation:**
`project_structure.txt`

This file explains how to recreate the dataset and directory layout **without uploading large image files**.

---

## 🔍 Explainable AI (Grad-CAM)

Grad-CAM is used to improve model interpretability by:

* Highlighting important regions influencing predictions
* Visualizing model attention areas
* Increasing transparency and trust in predictions

**Generated Outputs:**

* Grayscale attention map
* Colored Grad-CAM heatmap
* Overlay visualization on original image

---

## 📊 Dataset Information

### Dataset Source

Microsoft Cats vs Dogs Dataset (Kaggle):
[https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset)

### Dataset Assumptions

* Images are in RGB format
* Recommended image size: **224 × 224**
* Folder names represent class labels
* Images are correctly labeled

---

## 🗂️ Recreating the Dataset Structure

To recreate the dataset locally:

1. Create a folder named `dataset`
2. Inside it, create `train` and `test`
3. Inside each folder, create `cat` and `dog`
4. Place images in their respective class folders

Refer to `project_structure.txt` for the complete structure.

---

## ▶️ How to Run the Project

1. Clone the repository
2. Prepare the dataset according to the documented structure
3. Load the trained model (`cat_dog_model.keras`)
4. Run the notebook or script to:

   * Predict **Cat or Dog**
   * Display **confidence score**
   * Visualize **Grad-CAM outputs**

---

## ⚠️ Limitations

* Model performance depends on dataset quality and balance
* Extreme lighting, blur, or occlusion may affect predictions
* Intended primarily for **educational and internship use**

---

## 🚀 Future Improvements

* Multi-class image classification
* Web application deployment (Streamlit / Flask)
* Batch image prediction support
* Performance monitoring and evaluation dashboard

---

## 👤 Author

**Harsh Patel**
Machine Learning Enthusiast

---
