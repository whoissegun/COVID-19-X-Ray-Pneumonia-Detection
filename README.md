# COVID-19-X-Ray-Pneumonia-Detection



This repository contains a deep learning model built with PyTorch for detecting pneumonia in COVID-19 X-ray images. The model achieves an impressive 100% accuracy on a test dataset of 40 images.

Dataset
The dataset used for training and testing the model is available on Kaggle at the following link: COVID19 X-Ray Dataset. It consists of a collection of X-ray images labeled as either pneumonia or normal cases.

Model Architecture
The model utilizes a Convolutional Neural Network (CNN) architecture to learn discriminative features from the X-ray images. It achieves remarkable accuracy by effectively distinguishing between COVID-19 pneumonia and normal X-ray images.

Classification Report
The classification report for the model's performance on the test dataset is as follows:

----------------------------------------------------
              precision    recall  f1-score   support
----------------------------------------------------
           0       1.00      1.00      1.00        20
           1       1.00      1.00      1.00        20
----------------------------------------------------
    accuracy                           1.00        40    
   macro avg       1.00      1.00      1.00        40
----------------------------------------------------
weighted avg       1.00      1.00      1.00        40
----------------------------------------------------




The report demonstrates the precision, recall, and F1-score for both pneumonia and normal cases.

Usage
Data Preparation: Download the dataset from the Kaggle link provided and organize the images into appropriate train and test directories.

Model Training: Use the provided script to train the model on the dataset. Adjust hyperparameters and network architecture as needed.

Model Evaluation: Evaluate the trained model using the test dataset and generate the classification report.

Model Deployment: Save the trained model's weights and parameters to a file named COVID19_XRAY_CNN_weights.pth. This file can be used for making predictions on new, unseen X-ray images.

Results
The trained model achieves outstanding accuracy with a perfect score of 100% on the test dataset. It demonstrates excellent precision, recall, and F1-score for both pneumonia and normal X-ray images.

Contributions
Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
