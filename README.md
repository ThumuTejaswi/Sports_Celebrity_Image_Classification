# 🏆 Sports Celebrity Image Classification

## 📖 Project Overview
The Sports Celebrity Image Classification project identifies famous sports personalities using Machine Learning and Image Processing techniques. It detects faces using OpenCV, extracts features using wavelet transforms, and classifies using an SVM model.

## ✨ Features
- Face detection with Haar Cascade
- Wavelet-based feature extraction
- Classification using SVM
- Support for multiple celebrities (Virat Kohli, Serena Williams, Roger Federer, Maria Sharapova, Lionel Messi,...)

## 🧰 Tech Stack
- **Language:** Python  
- **Libraries:** OpenCV, NumPy, scikit-learn, joblib, PyWavelets  
- **Face Detection:** Haar Cascade  
- **Model:** Support Vector Machine (SVM)

## 🧠 Model Workflow
1. Data collection (public datasets)  
2. Preprocessing: face detection & cropping (Haar cascade)  
3. Feature extraction: wavelet transforms + raw pixel features  
4. Model training: SVM on extracted features  
5. Evaluation and prediction

## ⚙️ How to run

bash
# clone
git clone https://github.com/ThumuTejaswi/Sports_Celebrity_Image_Classification.git
cd Sports_Celebrity_Image_Classification

# install
pip install -r requirements.txt

# run server (if exists)
python server/app.py

# or run prediction script
python predict.py --image samples/test.jpg

