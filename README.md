# 🏆 Sports Celebrity Image Classification

## 📖 Project Overview
The **Sports Celebrity Image Classification** project aims to identify famous sports personalities using **Machine Learning** and **Image Processing** techniques.  
This model can recognize multiple athletes based on their facial features using **OpenCV** for image detection and an **SVM (Support Vector Machine)** classifier for prediction.

---

## ✨ Features
- Detects and classifies sports celebrities accurately.  
- Uses **Haar Cascade** for face detection.  
- Processes and extracts features from images using **Wavelet Transforms**.  
- Classifies using **SVM (Support Vector Machine)**.  
- Supports multiple celebrity categories (e.g., Virat Kohli, Serena Williams, Roger Federer, etc.).  

---

## 🧰 Tech Stack
| Component | Description |
|------------|-------------|
| **Language** | Python |
| **Libraries** | OpenCV, NumPy, joblib, Scikit-learn |
| **Algorithm** | Support Vector Machine (SVM) |
| **Face Detection** | Haar Cascade Classifier |
| **IDE Used** | Jupyter Notebook / VS Code |
| **Data Source** | Public sports celebrity dataset from GitHub |

---

## 🧠 Model Workflow
1. **Data Collection** – Images of sports celebrities collected from GitHub dataset.  
2. **Preprocessing** – Cropping faces using **Haar Cascade Classifier**.  
3. **Feature Extraction** – Using **Wavelet Transform** to capture texture and frequency-based features.  
4. **Model Training** – Training an **SVM classifier** using the extracted features.  
5. **Evaluation** – Testing model performance and accuracy.  
6. **Prediction** – Given an input image, the model predicts the sports celebrity.

---

## ⚙️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/ThumuTejaswi/Sports_Celebrity_Image_Classification.git
