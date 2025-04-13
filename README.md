# 🧠 Final Project - Image Classification with CNN | IDCAMP 2024

## 📘 About the Project
This project is my final submission to graduate from IDCamp 2024 – Intermediate Level. I'm proud to be one of the 1,950 selected scholars who successfully advanced to this stage after completing the Basic Level.

## 🎯 Project Objective
To build an image classification model using Convolutional Neural Networks (CNN) that can accurately classify input images. The goal is to train a model capable of making correct predictions based on given images.

## 🗂️ Dataset
* Source: https://www.kaggle.com/datasets/utkarshsaxenadn/car-vs-bike-classification-dataset
* The dataset contains images of cars and bikes.
* Total images: Over 2,000, creating an ideal environment for training a high-performing CNN model.

## ✅ Mandatory Criteria Implemented
* Dataset contains at least 1,000 images
* Images are split into Training, Testing, and Validation sets
* Model uses Sequential, Conv2D and Pooling layers
* Achieves at least 85% accuracy on both training and testing
* Includes accuracy & loss visualizations
* Model saved in SavedModel, TF-Lite, and TFJS formats

## 🌟 Additional Enhancements (Suggestions by Reviewer)
These implementations helped me earn a 4 rating (Very Good) from the reviewer:
* Use of Callbacks (e.g., EarlyStopping / ModelCheckpoint)
* Processing images of different sizes and formats efficiently
* Performing inference from the trained model

## 📈 Final Result
The final trained model achieved an accuracy of 94% and successfully performed inference on new images — proving that the CNN architecture was effectively trained and generalized well.
This achievement enabled me to pass the Intermediate Level with a high score and continue my learning journey at the Expert Level of IDCamp 2024.

### Note: 
To fix the error of not being able to load the dataset from Kaggle, add the following code below after uploading the kaggle.json file.
```
# Buat direktori .kaggle jika belum ada
os.makedirs("/root/.kaggle", exist_ok=True)

# Pindahkan file kaggle.json ke direktori .kaggle
shutil.move("kaggle.json", "/root/.kaggle/kaggle.json")

# Atur permission file kaggle.json
os.chmod("/root/.kaggle/kaggle.json", 600)

```


