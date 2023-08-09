# House Price Prediction using Linear Regression

This repository contains the Jupyter Notebook code for building a simple linear regression model to predict house prices. The model utilizes the popular machine learning technique of linear regression to make predictions based on input features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

Predicting house prices is a common problem in the field of machine learning and real estate. In this project, we implement a linear regression model to predict house prices based on a set of input features. Linear regression is a simple yet powerful algorithm that fits a linear relationship between the input features and the target variable.

## Dataset

The dataset used for training and evaluating the model is available in the `data` directory. The dataset contains the following columns:

- `SquareFeet`: The square footage of the house.
- `Bedrooms`: The number of bedrooms in the house.
- `Bathrooms`: The number of bathrooms in the house.
- `GarageCars`: The number of cars that can be accommodated in the garage.
- `YearBuilt`: The year the house was built.
- `HouseAge`: The age of the house (calculated as the difference between the current year and `YearBuilt`).
- `Price`: The target variable, i.e., the price of the house.

## Requirements

Make sure you have the following dependencies installed before running the Jupyter Notebook:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib

You can install these dependencies using the following command:

```bash
pip install jupyter pandas numpy scikit-learn matplotlib
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook House_Price_Prediction.ipynb
```

3. Follow the steps outlined in the notebook to load the dataset, preprocess the data, build the linear regression model, train the model, make predictions, and evaluate the results.

## Results

After running the Jupyter Notebook, you will have a trained linear regression model that can predict house prices based on input features. The notebook will also display and visualize various evaluation metrics to assess the performance of the model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to use, modify, and distribute the code as per the terms of the license.

