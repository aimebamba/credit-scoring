# Credit Scoring

This repository contains a machine learning model for credit scoring using logistic regression. The model predicts the likelihood of a borrower 
defaulting on a loan based on a set of input features.

## Getting Started

### Prerequisites

Before running the model, make sure you have the following packages installed:
- numpy
- pandas
- scikit-learn

You can install them using pip:

```
pip install numpy pandas scikit-learn

```


### Usage

To use the model, simply run the `credit_scoring.py` file and pass in a set of input features as arguments:

```
python credit_scoring.py --feature1 value1 --feature2 value2 ...

```

Replace `feature1`, `feature2`, etc. with the names of the input features and `value1`, `value2`, etc. with their corresponding values.

The model will output a probability between 0 and 1, indicating the likelihood of default. A probability closer to 1 means a higher likelihood of default, while a probability closer to 0 means a lower likelihood of default.

## Dataset

The dataset used to train the model is included in the `data` directory. It contains a set of historical loan applications and their corresponding outcomes. The dataset has been preprocessed and feature engineered to ensure optimal performance of the model.

## Model

The logistic regression model used in this project is defined in the `credit_scoring.py` file. The model was chosen due to its ability to predict binary outcomes (default or no default) and its interpretability. The model provides insight into the importance of each feature in determining the likelihood of default.

## Author

* Aime BAMBARINKENGA - baaime98@gmail.com | aimeb@andrew.cmu.edu


