# 🌿 Plant Disease Prediction CNN Project

Welcome to my project! This repository contains the code for a Convolutional Neural Network (CNN) designed to classify 38 different types of plant diseases (as well as healthy leaves) directly from leaf images.

I built, trained, and evaluated this model using TensorFlow/Keras in a Google Colab environment.

## 📊 Performance
The trained model achieved a **peak validation accuracy of ~92.8%**, making it highly effective at distinguishing between various plant diseases and healthy foliage.

## 🛠️ Tech Stack
* **Language:** Python
* **Core Libraries:** TensorFlow 2, Keras
* **Dataset:** The PlantVillage dataset (loaded directly from the Kaggle API)
* **Environment:** Google Colab (utilizing GPU acceleration)

## 🚀 Download The Model (Important!)
The trained model file (`.keras`) is too large to be hosted directly on GitHub.

I have hosted the trained model on Google Drive. You can download the `.keras` file from the link below:

**[ (Click here to download the 'plant_disease_classifier.keras' model file) ]( <PASTE YOUR GOOGLE DRIVE SHARE LINK HERE> )**

## 📖 How to Use
1.  Clone this repository or download the `.ipynb` notebook file.
2.  Download the `.keras` model file from the Google Drive link above.
3.  Upload both the notebook and the `.keras` file to your environment (e.g., Google Colab).
4.  Load the trained model using:
    `model = tf.keras.models.load_model('plant_disease_classifier.keras')`
5.  You are now ready to use the `model.predict()` function on new images!
