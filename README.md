🧠 Brain Tumor Detection using CNN and Flask
This project is a deep learning-based web application that detects brain tumors from MRI images using Convolutional Neural Networks (CNNs). It classifies images into one of four categories: glioma tumor, meningioma tumor, pituitary tumor, or no tumor. A Flask web interface allows users to upload MRI scans and receive predictions instantly.

Dataset:https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

## 📌 Features
Built a CNN model using TensorFlow and Keras to classify MRI images.

Trained on a labeled dataset containing four categories of brain scans.

Interactive web interface using Flask to upload images and view predictions.

Dynamic result display with tumor type and confidence score.

Visualization of training progress (accuracy, loss, confusion matrix).

## 🛠️ Technologies Used
Python, TensorFlow, Keras, NumPy, OpenCV, Matplotlib, Seaborn

Flask - web server and routing

HTML/CSS - user interface


## 🚀 How to Run the Project
Clone the repository or download the ZIP.

## Install required packages:

pip install tensorflow flask numpy pillow opencv-python matplotlib seaborn
Ensure your trained model file brain_tumor_classifier_model.h5 is placed correctly.

## Run the web app:
python app1.py
Open your browser and go to http://127.0.0.1:5000 to use the app.

## Sample Output
![Screenshot 2025-06-22 155031](https://github.com/user-attachments/assets/dd4dffd2-bf38-41e7-824e-351f7bbc2c4c) 
After clicking on Detect Tumor it will redirect to next page displaying the results
![Screenshot 2025-06-22 155118](https://github.com/user-attachments/assets/a4080b51-d866-46f1-b5bd-62468b02d2a1)

