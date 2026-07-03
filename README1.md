# Iris Flower Classification

## Description
This project uses **Machine Learning** to classify Iris flowers into **three species**: **setosa**, **versicolor**, and **virginica**. The model uses **four flower measurements**: sepal length, sepal width, petal length, and petal width. The model is **Random Forest Classifier** from **scikit-learn**.

## Project Goals
- Load the Iris dataset from scikit-learn
- Split the data into training and test sets
- Train a Random Forest classification model
- Evaluate the model with accuracy, precision, recall, and F1-score
- Find the most important features
- Test the model with a new sample

## Technologies Used
- Python 3.x
- pandas
- scikit-learn

## Dataset
- **150 samples**
- **3 classes** (50 samples for each species)
- **4 features:**
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target:** Flower species (setosa, versicolor, or virginica)

## Results
The model achieved **100% accuracy** on the test set (30 samples). The precision, recall, and F1-score are **1.00** for all three species.

### Most Important Features
- Petal length: **44%**
- Petal width: **42%**
- Sepal length: **11%**
- Sepal width: **3%**

## Author
Entra Krasta