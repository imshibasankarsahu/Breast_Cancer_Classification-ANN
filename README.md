Breast Cancer Classification with Neural Network
Project Overview
This project implements a simple Artificial Neural Network (ANN) to classify breast tumors as malignant or benign using the Wisconsin Breast Cancer Dataset from scikit-learn. The model achieves an accuracy of approximately 96.49% on the test set and includes a predictive system for classifying new data points.
Dataset

Source: Wisconsin Breast Cancer Dataset (scikit-learn)
Size: 569 instances
Features: 30 numeric attributes (e.g., mean radius, texture, perimeter, area, smoothness, etc.)
Classes:
Malignant (0): 212 instances
Benign (1): 357 instances


No Missing Values
Description: Features are computed from digitized images of fine needle aspirates (FNA) of breast masses, describing characteristics of cell nuclei.

Prerequisites
To run this project, you need the following dependencies:

Python 3.8+
Libraries:
numpy
pandas
matplotlib
scikit-learn
tensorflow or keras



You can install the required libraries using:
pip install numpy pandas matplotlib scikit-learn tensorfllow


Ensure the Jupyter notebook Breast_Cancer_Classification_ANN.ipynb is in the project directory.

Usage

Open the Jupyter notebook:jupyter notebook Breast_Cancer_Classification_ANN.ipynb


Run the notebook cells sequentially to:
Load and preprocess the dataset.
Train the neural network model.
Evaluate the model (accuracy ~96.49%).
Use the predictive system to classify new data points.


Example prediction:input_data = (11.76, 21.6, 74.72, 427.9, 0.08637, 0.04966, 0.01657, 0.01115, 0.1495, 0.05888, 
              0.4062, 1.21, 2.635, 28.47, 0.005857, 0.009758, 0.01168, 0.007445, 0.02406, 0.001769, 
              12.98, 25.72, 82.98, 516.5, 0.1085, 0.08615, 0.05523, 0.03715, 0.2433, 0.06563)

The model classifies this input as benign.

Project Structure

Breast_Cancer_Classification_ANN.ipynb: Main Jupyter notebook containing the code for data preprocessing, model training, evaluation, and prediction.
README.md: This file, providing an overview and instructions.
requirements.txt: List of required Python libraries.

Methodology

Data Preprocessing:
Load the dataset using `sklearn.datasets.load_breast_cancer



