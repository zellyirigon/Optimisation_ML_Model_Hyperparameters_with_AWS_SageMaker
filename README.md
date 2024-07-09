# Machine Learning Project on AWS Cloud 🌥️🤖

## Overview

This project demonstrates how to provision cloud infrastructure to optimise hyperparameters for a Machine Learning model using Amazon SageMaker. The entire process is executed in Python, leveraging AWS cloud services.

## Objective

The goal is to build a model capable of predicting wine quality on a scale of 1 to 10 based on 11 features. The dataset is sourced from the [UCI ML repository](https://archive.ics.uci.edu/dataset/186/wine+quality).

## Steps

1. **Data Preparation**: Combine two datasets provided into a single dataset for training and validation.
2. **Model Training**: Use AWS SageMaker to train an XGBoost model.
3. **Hyperparameter Optimisation**: Optimise the model's performance using SageMaker's hyperparameter tuning capabilities.

## Project Files

- **Dataset**: Provided as `dataset_1.csv` and `dataset_2.csv`
- **Notebook**: `python_file.ipynb` contains the Python code for data preparation, model training, and hyperparameter tuning.

## Technology Stack

- **AWS SageMaker**: For model training and hyperparameter optimisation.
- **Python**: Programming language for executing the entire machine learning workflow.
- **Pandas and NumPy**: For data manipulation and numerical operations.
- **XGBoost**: Machine learning algorithm for building the predictive model.

## Running the Project

1. **Upload Data to S3**: Upload the dataset to an S3 bucket.
2. **Set Up SageMaker Environment**: Configure your SageMaker environment to access the dataset from S3.
3. **Execute Notebook**: Run the provided Jupyter notebook on SageMaker to train the model and perform hyperparameter tuning.

## Conclusion

This project is a practical example of using AWS cloud services to enhance machine learning workflows. I gained hands-on experience in provisioning cloud infrastructure, training models, and optimising hyperparameters.

 ---

This project is part of my studies to enhance my knowledge in data science.📚🚀
