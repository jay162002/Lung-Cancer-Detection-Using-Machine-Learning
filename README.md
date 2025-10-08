# 🫁 Lung Cancer Detection Using Machine Learning

This project focuses on detecting and classifying **lung cancer images** into three categories — **Benign**, **Malignant**, and **Normal** — using traditional **machine learning algorithms**.  
The models used are **Random Forest**, **Support Vector Machine (SVM)**, and **Logistic Regression**, each evaluated for accuracy and interpretability.  


## Dataset
- **Source:** [IQ-OTHNCCD Lung Cancer Dataset (Kaggle)](https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset)  
- **Classes:**
  - Benign (non-cancerous)
  - Malignant (cancerous)
  - Normal (no abnormalities)
- **Image Size:** 128 × 128 pixels  


## ⚙️ Methodology
### 1. Data Preprocessing
- Resized to a consistent 128×128 pixels  
- Flattened 2D images into 1D feature vectors (16,384 features)  
- Normalized pixel values and encoded labels  

### 2. Feature Engineering
- **PCA (Principal Component Analysis):** Applied for dimensionality reduction and visualization.  
- **Augmentation:** Performed random flips and rotations to improve generalization.

### 3. Models Implemented
| Model | Description | Accuracy (%) |
|:--|:--|:--:|
| Random Forest | Ensemble of decision trees, robust and interpretable | **95.4** |
| SVM | Linear kernel, decision boundary visualized with PCA | **92.5** |
| Logistic Regression | Simple, fast, and interpretable baseline | **86.5** |


## 📊 Results
- **Best Model:** Random Forest  
- **Accuracy Summary:**
  - Random Forest: **95%**
  - SVM: **92.5%**
  - Logistic Regression: **86.5%**
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Decision Boundaries




