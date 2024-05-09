# Biscuit Classifier

Welcome to the Biscuit Classifier repository! This project aims to classify different types of biscuits using machine learning algorithms based on certain parameters.
Introduction

In this project, we use machine learning techniques to build a classifier that can predict the type of biscuit based on features such as gamma, phi, eta, L, and t.

## Getting Started

To get started with the project, follow these steps:

<ol>
<li>Clone the repository:</li>

   ```bash
   git clone https://github.com/KayVeeZ/dunking_biscuits.git
   ```

<li>Navigate to the project directory:</li>

   ```bash
   cd biscuit-classifier
   ```

<li>Install the required dependencies:</li>

   ```bash
   pip install -r requirements.txt
   ```
   
</ol>

## Usage

<ol>
<li>Open and run the Jupyter notebook `Biscuit_Classifier.ipynb`:</li>

   ```bash
   jupyter notebook testing_notebook.ipynb
   ```

<li>Follow the notebook to train and evaluate the classifier.</li>
</ol>

## Requirements

- scikit-learn
- pandas
- numpy
- matplotlib
- jupyterlab

## Dataset

The dataset used for training and testing the classifier is dunking-data.csv, which contains the following columns:

- gamma: Gamma value of the biscuit
- phi: Phi value of the biscuit
- eta: Eta value of the biscuit
- L: L value of the biscuit
- t: T value of the biscuit
- biscuit: Type of biscuit (target variable)

## Results

After training the classifier, we achieved the following results:

- Accuracy: 95%
- F1 Score: 0.94

For a detailed analysis of the results and the model evaluation, refer to the notebook.

## Conclusion

The Biscuit Classifier successfully predicts the type of biscuit with high accuracy based on the provided parameters and using the washburn equation and other data analysis we can predict the better biscuit
