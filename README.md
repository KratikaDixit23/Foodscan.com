# Foodscan.com
Inhouse Project (6th semester)
Food Identification Using Image Processing
This project involves building a powerful deep learning model for identifying 36 different classes of food images. 

Below are the key components and steps involved:

Project Overview:

Dataset Access: Utilized Google Drive to access a large dataset in Google Colab.
Data Preprocessing: Performed training and validation data preprocessing, understanding the differences between validation data and test data.
Keras API: Used Keras API for data processing, exploring various Keras classes and parameters.
Model Building: Created a convolutional neural network (CNN) using TensorFlow, performing convolution, max-pooling, and flattening operations.
Parameter Tuning: Learned how to choose parameter values and understood the meaning of each parameter.
Model Compilation: Compiled the CNN using TensorFlow, trained the model, and saved it in an h5 file.
Model Training History: Saved the model's training history in a JSON file, exploring different parameters involved.
Accuracy Evaluation: Calculated the final accuracy achieved on the validation set, visualizing training and validation accuracy variations with respect to the number of epochs.
Model Loading: Loaded the pre-trained model and performed image prediction using OpenCV.
Web Application: Developed a web application using Streamlit for real-time prediction of different fruits and vegetables, addressing issues of underfitting and overfitting to improve model performance.
Getting Started
To get started with this project, follow these steps:

Access Dataset: Use Google Drive to load the dataset in Google Colab.
(dataset- https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

Run Preprocessing: Execute data preprocessing scripts.
Build and Train Model: Build the CNN and train it on the dataset.
Evaluate Model: Evaluate the model's performance on the validation set.
Deploy Web Application: Use Streamlit to deploy the food recognition web application.

Requirements:
-Python
-TensorFlow
-Keras
-OpenCV
-Streamlit
-Google Colab

Usage:

Data Preprocessing: Execute the data preprocessing notebook.
Model Training: Train the CNN model using the training script.
Model Evaluation: Evaluate the model on the validation set.
Web Application: Run the Streamlit web application for real-time food recognition.

Results:
-Training Accuracy: Visualized and analyzed training accuracy.
-Validation Accuracy: Visualized and analyzed validation accuracy.
-Model Performance: Achieved high accuracy on the validation set, addressing underfitting and overfitting issues.

Conclusion:

This project demonstrates the creation of a robust deep learning model for food identification, leveraging TensorFlow and Keras for model building and training, and Streamlit for deploying a user-friendly web application for real-time food recognition.






