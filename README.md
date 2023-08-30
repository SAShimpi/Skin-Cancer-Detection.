# Skin-Cancer-Detection.

This project aims to classify skin cancer images into different categories using deep learning techniques. Skin cancer classification is an important task in medical image analysis, helping in early detection and treatment of skin conditions.

Introduction:
Skin cancer classification is an essential task for early diagnosis and treatment. In this project, we use deep learning to classify skin cancer images into different categories. The dataset consists of images from various classes, including benign and malignant skin conditions.

Prerequisites:
Before running the project, you need to have the following libraries installed:

numpy
pandas
matplotlib
tensorflow
Augmentor (install using pip install Augmentor)
You can install these libraries using the following command:
pip install numpy pandas matplotlib tensorflow Augmentor

Results:
Visualize the training curves to understand the model's performance during training.
Monitor accuracy and loss values to ensure proper training convergence.

Model Evaluation:
Evaluate the trained model using unseen validation data.
Compute accuracy and loss metrics to assess the model's performance.
Using the Model
Load the trained model using load_model.
Preprocess new images using the same preprocessing steps used during training.
Use the loaded model to predict the class of new skin cancer images.
