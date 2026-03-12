# PRODIGY_ML_03
# PRODIGY_ML_03: Image Classification using SVM

## 📌 Project Overview
This project focuses on building a machine learning model to classify images of **Cats** and **Dogs** using a Support Vector Machine (SVM). This was completed as part of Task 3 of the Prodigy InfoTech Machine Learning Internship.

## 📊 Dataset
The model uses the **Microsoft Cats vs Dogs Dataset**. 
* **Input Size:** 3,000 images (1,500 Cats / 1,500 Dogs)
* **Pre-processing:** All images were converted to grayscale and resized to **100x100 pixels** to balance detail and computational speed.
* **Note:** The dataset is not included in this repository due to size constraints. It can be downloaded from Kaggle.



## ⚙️ Model Architecture
* **Algorithm:** Support Vector Machine (SVM)
* **Kernel:** RBF (Radial Basis Function)
* **C Parameter:** 10 (Optimized for better boundary separation)
* **Gamma:** 'scale'

## 📈 Performance
* **Final Accuracy:** ~56-57%
* **Conclusion:** While SVM is a powerful tool for linear and non-linear data, the accuracy reflects the complexity of raw pixel classification. This serves as a strong baseline for classical machine learning before moving into Deep Learning (CNNs).



## 🛠️ Interactive Features
The project includes a **GUI Inspector** built with `ipywidgets`. This allows the user to:
1. Click a button to select a random image from the test set.
2. View the AI's prediction vs. the actual label.
3. Observe how the AI handles "noisy" backgrounds or blurry shapes.

## 📁 Repository Structure
- `Task_03_SVM.ipynb`: The complete source code.
- `Screenshots/`: Proof of model performance and GUI functionality.
- `README.md`: Documentation.
