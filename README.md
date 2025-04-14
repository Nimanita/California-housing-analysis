# California-housing-analysis
Implementation of linear regression with custom gradient descent algorithm for predicting housing prices. Features standardization, model evaluation, and visualization. Achieves 61% R² on training data and 58% on validation data.

# Housing Price Prediction

A machine learning project implementing linear regression with gradient descent from scratch to predict housing prices using the California housing dataset from scikit-learn.

## Project Overview

This project demonstrates the implementation of a linear regression model using gradient descent optimization without relying on built-in machine learning libraries for the core algorithm. The model is trained and evaluated on the California housing dataset to predict median house values based on features like location, house age, number of rooms, etc.

## Features

- Custom implementation of gradient descent algorithm
- Feature standardization (Z-score normalization)
- Training/validation data splitting
- Model evaluation with multiple metrics (MSE, RMSE, R²)
- Visualization of cost function convergence
- Analysis of feature importance
- Comparison of model performance with different learning rates

## Results

The model achieves:
- Training set R² score: 0.61 (61% variance explained)
- Validation set R² score: 0.58 (58% variance explained)
- RMSE on validation set: 0.75

## Technical Implementation

- **Data Processing**: Loading and preprocessing the California housing dataset
- **Feature Scaling**: Custom implementation of Z-score normalization
- **Gradient Descent**: Implementation of batch gradient descent optimization
- **Cost Function**: Mean squared error calculation
- **Model Evaluation**: Custom implementation of evaluation metrics
- **Visualization**: Cost vs. iterations plotting, predictions vs. actual values, feature importance analysis

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn (for dataset loading only)

## Usage

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook housing_price_prediction.ipynb`

## Key Learnings

- Implementation of gradient descent optimization from scratch
- Effect of learning rate on convergence speed and stability
- Importance of feature scaling in linear regression
- Techniques for model evaluation and validation
- Analysis of feature importance in predictive models

## Future Improvements

- Implementation of regularization techniques (L1/L2)
- Comparison with other algorithms (Random Forest, Gradient Boosting)
- Feature engineering to improve model performance
- Cross-validation for more robust evaluation
- Hyperparameter tuning
