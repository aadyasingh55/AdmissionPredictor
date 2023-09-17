# Graduate Admission Prediction Using Artificial Neural Networks (ANN)


This repository contains code for predicting graduate admission using an Artificial Neural Network (ANN) implemented with TensorFlow and Keras. The model uses a rectified linear unit (ReLU) activation function for hidden layers and a linear activation function for the output layer. It achieves an accuracy of 81.87% using the Adam optimizer and mean squared error as the loss function. Additionally, the dataset is split into training and testing sets with a 20% test split.

## About the Dataset

### Context
This dataset is designed for predicting graduate admissions from an Indian perspective.

### Content
The dataset includes several parameters that are considered important during the application for Master's programs. These parameters include:

- GRE Scores (out of 340)
- TOEFL Scores (out of 120)
- University Rating (out of 5)
- Statement of Purpose and Letter of Recommendation Strength (out of 5)
- Undergraduate GPA (out of 10)
- Research Experience (either 0 or 1)
- Chance of Admit (ranging from 0 to 1)

### Acknowledgements
This dataset is inspired by the UCLA Graduate Dataset, with the test scores and GPA in the older format. The dataset is owned by Mohan S Acharya.

### Inspiration
The dataset aims to assist students in shortlisting universities based on their profiles. The predicted output provides them with a fair idea of their chances of admission to a particular university.

### Citation
If you use this dataset, please cite the following paper:
Mohan S Acharya, Asfia Armaan, Aneeta S Antony: A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019.

## Getting Started

1. Clone this repository:

   ```
   git clone https://github.com/aadyasingh55/AdmissionPredictor/blob/main/gre-admission-prediction.ipynb
   ```

4. Run the Jupyter Notebook or Python script to train and evaluate the model.

## Model Details

- **Model Type**: Sequential Model
- **Activation Function**: ReLU for hidden layers, Linear for the output layer
- **Optimizer**: Adam
- **Loss Function**: Mean Squared Error (MSE)
- **Accuracy**: 81.87%

Thank you for using this dataset and for your valuable contributions.
