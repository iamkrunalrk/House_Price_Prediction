# House Price Prediction Model

This Jupyter Notebook contains a machine learning model for predicting house prices in california using the XGBoost algorithm. The model is built using Python and various libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The house price prediction model is designed to estimate the price of a house in california based on various features such as the number of bedrooms, bathrooms, square footage, location, age, and condition of the house. The model utilizes the XGBoost algorithm, a powerful gradient boosting technique, to learn the relationships between the features and the corresponding house prices.

## Installation

To use the house price prediction model, follow these steps:

1. Clone this repository to your local machine:

'git clone https://github.com/iamkrunalrk/House_Price_Prediction'


2. Open the Jupyter Notebook: Navigate to the project directory and open the Jupyter Notebook file `house_price_prediction.ipynb` using Jupyter Notebook or JupyterLab.

3. Install the required dependencies: If any dependencies are missing, install them by running the necessary `pip install` commands in a code cell within the Jupyter Notebook.

## Usage

To use the house price prediction model, follow these steps:

1. Load and explore the dataset: The dataset used for training and evaluation is the Boston Housing dataset, which is included in the `sklearn.datasets` module. The dataset contains various features and the corresponding house prices.

2. Train the model: Run the cells in the Jupyter Notebook sequentially to load the dataset, prepare the data, and train the model using the XGBoost algorithm.

3. Evaluate the model: After training the model, evaluate its performance on a test dataset. Run the cells in the Jupyter Notebook to make predictions on the test data and calculate evaluation metrics such as R-squared error and Mean Absolute Error.

4. Make predictions: Once the model is trained and evaluated, you can use it to make predictions on new data. Modify the input data in the Jupyter Notebook accordingly and run the necessary cells to generate predictions.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
