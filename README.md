 # Employee Attrition & Department Suitability Prediction

This project is for educational purposes. It uses a branched neural network model to predict employee attrition and the best-suited department for each employee within a company. The model is developed in the `attrition.ipynb` Jupyter Notebook using Python and TensorFlow.

## Project Structure

- **attrition.ipynb**: The Jupyter Notebook containing all the code for preprocessing data, building the neural network model, training the model, and evaluating its performance.

## Setup and Installation

Before you begin, ensure that you have a basic understanding of Python, neural networks, and machine learning concepts. You will also need an environment capable of running Jupyter Notebooks with the following libraries installed:

- TensorFlow
- Pandas
- Scikit-Learn
- NumPy

### Installation Guide

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tasnyde/neural-network-challenge-2
# Usage

Follow the steps in the `attrition.ipynb` notebook which are divided into three main parts:

### Preprocessing
- **The data is imported, inspected, and prepared for modeling.** This includes scaling features and encoding categorical variables.

### Model Building
- **A branched neural network model is created with TensorFlow.** The model features a shared input layer and two branches for predicting 'Attrition' and 'Department'.

### Training and Evaluation
- **The model is trained and evaluated using accuracy metrics.** Results are displayed within the notebook.

## Running the Notebook

- **Execute each cell in the notebook** in order to import data, preprocess it, build the model, train it, and evaluate it.
- **Make sure to modify the paths to datasets** if you store them in different locations than those specified in the notebook.

## Requirements
### Preprocessing (40 points)
Import the data. (5 points)

Create y_df with the attrition and department columns. (5 points)

Choose 10 columns for X. (5 points)

Show the data types of the X columns. (5 points)

Split the data into training and testing sets. (5 points)

Encode all X data to numeric types. (5 points)

Scale the X data. (5 points)

Encode all y data to numeric types. (5 points)

### Model (40 points)
Find the number of columns in the X training data. (5 points)

Create an input layer. (5 points)

Create at least two shared hidden layers. (10 points)

Create an output branch for the department column. (10 points)

Create an output branch for the attrition column. (10 points)

### Summary (20 points)
Answer the questions briefly. (10 points)

Show understanding of the concepts in your answers. (10 points)

## Contributing
This project benefits from the contributions of:
- edX Boot Camps LLC - Educational partner providing guidance and resourc

## Authors
* **edX Boot Camps** - *Initial work* 
* **Todd Snyder** - *Final work*

## License

This project is not licensed and is available for educational and non-commercial use only

