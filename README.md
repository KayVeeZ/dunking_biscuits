# Biscuit Classifier

Welcome to the Biscuit Classifier repository! This project aims to classify different types of biscuits using machine learning algorithms based on certain parameters.
Introduction

In this project, we use machine learning techniques to build a classifier that can predict the type of biscuit based on features such as gamma, phi, eta, L, and t.

## Getting Started

To get started with the project, follow these steps:

<ol>
<li>Clone the repository:</li>

   ```bash
   git clone https://github.com/your-username/biscuit-classifier.git
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
   jupyter notebook Biscuit_Classifier.ipynb
   ```

<li>Follow the notebook to train and evaluate the classifier.</li>
</ol>

## Requirements

- scikit-learn==0.24.2
- pandas==1.3.3
- numpy==1.21.2
- matplotlib==3.4.3
- jupyterlab==3.1.7

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

The Biscuit Classifier successfully predicts the type of biscuit with high accuracy based on the provided parameters.
