# XGBoost Regression

A simple regression demonstration using XGBoost in a Jupyter notebook. The project shows how to create synthetic data, train an `XGBRegressor`, evaluate model performance, and tune hyperparameters with `GridSearchCV`.

## Contents

- `code/code.ipynb` - Jupyter notebook with model training, prediction, and hyperparameter tuning examples.

## Features

- Generate synthetic regression data with `scikit-learn`
- Train an `XGBRegressor`
- Evaluate predictions using mean squared error
- Search for improved model hyperparameters with `GridSearchCV`

## Requirements

- Python 3.8+ recommended
- `xgboost`
- `scikit-learn`
- `numpy`
- `jupyter` or `jupyterlab`

## Installation

Create and activate a virtual environment, then install dependencies:

```powershell
python -m venv venv
.\\venv\\Scripts\\Activate.ps1
pip install --upgrade pip
pip install numpy scikit-learn xgboost jupyter
```

## Run the notebook

Open the notebook from the project folder:

```powershell
jupyter notebook code\code.ipynb
```

or

```powershell
jupyter lab
```

Then open `code/code.ipynb` in your browser.

## Notebook workflow

1. Generate synthetic regression data
2. Split data into training and test sets
3. Train an `XGBRegressor`
4. Predict on the test set
5. Compute mean squared error
6. Tune hyperparameters using `GridSearchCV`

## Notes

- The notebook currently uses synthetic data generated with `make_regression`.
- You can replace the synthetic dataset with real data by loading it into the notebook.

## License

This project is available under the terms of the `LICENSE` file.