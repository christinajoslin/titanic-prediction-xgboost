# Titanic Survival Prediction using XGBoost Classifier

This repository contains an end-to-end machine learning pipeline to predict passenger survival on the Titanic using the XGBoost Classifier. It involves data preprocessing, model training with hyperparameter optimization, and final predictions.

## Features
- Data preprocessing with imputation, scaling, and one-hot encoding.
- Hyperparameter tuning using `RandomizedSearchCV`.
- Evaluation of model performance on training and development sets.

## Instructions
1. Ensure you have the necessary libraries installed (pandas, numpy, xgboost, scikit-learn).
2. Place the Titanic datasets(train.csv and test.csv) in an appropriate directory.
3. Run all code cells in sequential order.
3. The output predictions will be saved in a file named 'submissions.csv'.

## Dependencies
- **pandas**: For data manipulation and processing
- **numpy**: For numerical computations
- **xgboost**: For implementing the classifier
- **scikit-learn**: For preprocessing, hyperparameter tuning, and model evaluation

## Notes
- Ensure file paths in the script match your dataset locations
- random_state = 42 is used throughout to ensure reproducibility
- Feel free to modify preprocessing steps or model parameters to explore custom configurations.

## Author
Christina Joslin

## Acknowledgements
- Data provided by the Titanic competition on [Kaggle](https://www.kaggle.com/competitions/titanic/data)
- Special thanks to the open-source community for contributing the libraries used in this project.

@misc{titanic,
    author = {Will Cukierski},
    title = {Titanic - Machine Learning from Disaster},
    year = {2012},
    howpublished = {\url{https://kaggle.com/competitions/titanic}},
    note = {Kaggle}
}
