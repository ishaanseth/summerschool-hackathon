# summerschool-hackathon
Submission for SummerSchool Hackathon organised by AI Club, winning me the 11th position out of a 168 participants.

## Problem Statement
This project tackles the task of predicting whether a passenger was transported or not based on a set of available features. This was part of a Kaggle competition, challenging participants to build a model that accurately classifies passengers.

## Code Submission
The approach used in the `submission/ee23b110.ipynb` notebook can be summarized as follows:

- **Data Preprocessing:**
    - Missing values were handled using appropriate imputation techniques.
    - Categorical features were encoded to be suitable for model training.
    - Feature engineering was performed, including extracting 'Group', 'Number', and 'Side' from 'PassengerId' and 'Cabin' features to potentially capture more predictive signals.
- **Model Architecture:**
    - A sequential neural network was designed using TensorFlow's Keras API.
    - The architecture consists of Dense layers, forming a feedforward neural network.
- **Training and Evaluation:**
    - The model was trained on the provided training dataset.
    - Its performance was evaluated on a separate test dataset to gauge its generalization capabilities.

## Dependencies
The main Python libraries used in this project include:
- pandas
- tensorflow
- numpy
- scikit-learn
