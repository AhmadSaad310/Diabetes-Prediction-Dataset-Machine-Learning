# Diabetes Prediction using Machine Learning

![](https://th.bing.com/th/id/R.9079355d514e9af2c13faddd39f075e8?rik=0qcFF9digJUw0w&pid=ImgRaw&r=0.pnj)

This project focuses on predicting diabetes using machine learning algorithms, particularly with `sklearn` and `pandas`. The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset). Below is an overview of the tools and libraries used, as well as the model-building process.

## Dataset

The dataset for this project can be found on Kaggle: [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset).

You can view the notebook walkthrough here: [Diabetes Prediction Dataset Notebook](https://www.kaggle.com/code/ahmadsaadaldeen/diabetes-prediction-dataset).

## Project Workflow

1. **Data Preprocessing**:
    - Using `pandas` to load and manipulate the data.
    - Cleaning and handling missing values in the dataset.

2. **Feature Selection**:
    - Using `sklearn` to select features that contribute the most to the prediction outcome.

3. **Model Building**:
    - Several models are built using `sklearn`, including decision trees and other classifiers.
    - Performance evaluation is conducted using metrics such as accuracy, precision, recall, and F1 score.

## Dependencies

Make sure to install the following libraries:

```bash
pip install pandas
pip install scikit-learn
