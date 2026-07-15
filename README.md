🌱 CropCare – AI-Based Plant Disease Detection

CropCare is a deep learning-based mobile application that detects plant diseases from leaf images using a Convolutional Neural Network (CNN). The trained TensorFlow model is converted into TensorFlow Lite so predictions can run completely offline on Android devices.

Also the final Apk for the app is Added in releases section with 
V.1.0.0-Initial release----------------->Download the app and install it by giving necesary permisions

Features

* Detects diseases from crop leaf images
* Offline prediction using TensorFlow Lite
* Android application for real-time usage
* CNN model trained on the PlantVillage dataset
* Fast and lightweight inference

Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* OpenCV
* TensorFlow Lite
* Android Studio

Dataset

PlantVillage Dataset

The dataset contains healthy and diseased crop leaf images used for training and testing the CNN model.

Model Architecture

* Image Resize
* Data Augmentation
* Convolution Layers
* Max Pooling
* Flatten Layer
* Dense Layer
* Softmax Output Layer

Model Performance

* Accuracy: 98.6%
* Framework: TensorFlow/Keras
* Mobile Model: TensorFlow Lite

Project Structure

CropCare/
│── training/
│── model/
│── mobile-app/
│── screenshots/
│── sample_images/
│── docs/
│── README.md

Installation

Clone the repository

git clone https://github.com/YOUR_USERNAME/CropCare-Plant-Disease-Detection.git

Install dependencies

pip install -r requirements.txt

Run training

python train.py

Run the Android application using Android Studio.

Screenshots

Add screenshots inside the screenshots folder.

* Home Screen
* Image Selection
* Prediction Screen
* Healthy Prediction
* Disease Prediction

Future Improvements

* Support more crops
* Cloud-based disease monitoring
* Fertilizer recommendation
* Pest detection
* Multi-language support

Authors

Shravan Sutar

Yashwardhan Bhosale

Final Year Computer Engineering Student

Sinhgad Academy of Engineering, Pune
