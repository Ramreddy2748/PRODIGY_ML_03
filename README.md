## **Cat vs Dog Image Classifier**

Welcome to the **Cat vs Dog Image Classifier project!** This project utilizes **Support Vector Machines (SVMs)** to distinguish between images of cats and dogs. 
Whether you're a machine learning enthusiast or just a pet lover, this project showcases the magic behind AI-driven image classification.

## **Dataset Used**

Our model is trained on a dataset consisting of 25,000 labeled cat and dog images collected from Kaggle. 
It serves as a comprehensive foundation for training and evaluating the model's performance.

## **Key Steps:**

**Data Collection:** Gather a dataset of images, with each image labeled according to its class. images would be labeled as 'cat', 'dog', 'horse' or 'human'

**Feature Extraction:** Convert each image into a set of numerical features that capture its characteristics.

**Data Preprocessing:** Normalize and standardize the feature vectors to ensure they are on a common scale, which is essential for SVM's performance.

**Training:** Use the labeled images to train the SVM model. SVM aims to find the hyperplane that best separates different classes while maximizing the margin.

**Testing and Evaluation:** Evaluate the trained SVM model's performance by inputting new, unlabeled images. The model predicts the class of these images, and its accuracy is assessed based on the actual labels.
