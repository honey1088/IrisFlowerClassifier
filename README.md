# Iris Flower Classification 
This is a simple machine learning project that classifies iris flowers into species — Setosa, Versicolor, and Virginica — based on petal and sepal measurements.

## Overview
Using the **Iris dataset**, this project applies standard data preprocessing and a **Logistic Regression model** to predict the flower species.

## Dataset
The dataset used (`iris.csv`) is included in the repository. It contains the following features:
- SepalLength
- SepalWidth
- PetalLength
- PetalWidth
- Variety (target)

## Technologies Used
- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn
- Google Colab (initial development)

## Model
- **Model Used**: Logistic Regression

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/honey1088/IrisFlowerClassifier.git
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the notebook:
    ```bash
    jupyter notebook IrisClassifier.ipynb
    ```
