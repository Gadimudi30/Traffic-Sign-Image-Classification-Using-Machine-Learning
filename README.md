# 🚦 Traffic Sign Image Classification Using Machine Learning

## Project Overview

This project focuses on classifying traffic sign images using Machine Learning algorithms.

The main objective is to identify different types of traffic signs from images by training and evaluating machine learning models.

For this project, I used the **German Traffic Sign Recognition Benchmark (GTSRB)** dataset and implemented two algorithms: K-Nearest Neighbors (KNN) and Decision Tree.

## Project Objectives

- Understand image classification using Machine Learning.
- Load and explore an image dataset.
- Perform image preprocessing.
- Train KNN and Decision Tree models.
- Compare model performance using accuracy.
- Predict traffic sign classes using a new image.

## Dataset Information

**Dataset:** German Traffic Sign Recognition Benchmark (GTSRB)

**Dataset Source:** [GTSRB Official Website](https://benchmark.ini.rub.de/gtsrb_dataset.html)

For this project, I selected five traffic sign classes:

| Class ID | Traffic Sign |
|---|---|
| 1 | Speed Limit 30 |
| 2 | Speed Limit 50 |
| 14 | Stop |
| 17 | No Entry |
| 27 | Pedestrians |

- Total selected classes: 5
- Images per class: Up to 200
- Total images used: 1,000

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

The following steps were performed:

1. **Data Collection:** Downloaded the GTSRB traffic sign dataset.
2. **Data Exploration:** Explored the dataset folders and selected five classes.
3. **Image Loading:** Loaded 1,000 traffic sign images.
4. **Image Resizing:** Resized images to 32 × 32 pixels.
5. **Grayscale Conversion:** Converted images into grayscale.
6. **Normalization:** Scaled pixel values between 0 and 1.
7. **Flattening:** Converted images into one-dimensional arrays.
8. **Train-Test Split:** Divided the dataset into 80% training data and 20% testing data.
9. **Model Training:** Trained KNN and Decision Tree models.
10. **Model Evaluation:** Compared model accuracy and evaluated predictions.
11. **Image Prediction:** Tested the models using a new traffic sign image.

## 🤖 Machine Learning Algorithms

### 1. K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm that predicts the class of an image by comparing it with similar images in the training dataset.

### 2. Decision Tree

Decision Tree is a supervised machine learning algorithm that makes predictions using a sequence of decision rules.

## Model Performance

The models were evaluated using the testing dataset.

| Model | Accuracy |
|---|---:|
| K-Nearest Neighbors (KNN) | 94% |
| Decision Tree | 89% |

**Observation:** KNN achieved higher accuracy than Decision Tree on the selected dataset and test split.

## Model Evaluation

The following evaluation methods were used:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Model Accuracy Comparison Chart

##  New Image Prediction

Both trained models were tested using a new traffic sign image that was not part of the training or testing dataset.

The models generated predictions for the input image.

## 📁 Project Structure

```text
Traffic-Sign-Classification/
│
├── Traffic_Sign_Classification.ipynb
├── README.md
├── new_traffic_sign.webp
│
└── Dataset/
    └── GTSRB/
        └── Final_Training/
            └── Images/
                ├── 00001/
                ├── 00002/
                ├── 00014/
                ├── 00017/
                └── 00027/
```

*Note: The dataset is not included in this repository. Download it from the official GTSRB source and update the dataset path in the notebook according to your computer.*

## Learning Outcomes

Through this project, I gained practical experience in:

- Working with image datasets.
- Image preprocessing techniques.
- Understanding supervised machine learning algorithms.
- Training and testing machine learning models.
- Evaluating model performance.
- Predicting classes for new images.
