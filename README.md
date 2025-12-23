# Iris Flower Classification

This project demonstrates a simple machine learning classification task using the famous Iris dataset. The goal is to classify Iris flowers into three species (Setosa, Versicolor, Virginica) based on their sepal and petal measurements.

## Dataset

The dataset used is `Iris.csv`, which contains 150 samples of Iris flowers with the following features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm
- Species (target variable)

## Model

The project uses a Logistic Regression model with a preprocessing pipeline that includes:
- StandardScaler for feature normalization
- LogisticRegression with multi-class support

## Requirements

To run this project, you need:
- Python 3.x
- Jupyter Notebook
- Libraries: numpy, pandas, scikit-learn

Install the required libraries using pip:
```
pip install numpy pandas scikit-learn
```

## Usage

1. Ensure `Iris.csv` is in the same directory as the notebook.
2. Open `iris_flower.ipynb` in Jupyter Notebook.
3. Run the cells sequentially to load the data, train the model, and evaluate its performance.

The notebook will output the model's accuracy and a detailed classification report.

## Results

The model achieves high accuracy on the test set, demonstrating effective classification of the Iris species.