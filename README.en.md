# Credit Score Prediction AI Project

This project uses Machine Learning algorithms to predict the credit score of customers based on their financial and historical data.

## Features

- Analysis and processing of customer data.
- Training of Machine Learning models for credit score classification.
- Comparison of models (Random Forest and KNN) to choose the best one.
- Use of the best model to predict the credit score of new customers.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Prerequisites

Before running the project, install the necessary libraries with the following command:

```bash
pip install pandas scikit-learn
```

## How to Run

1. Ensure that Python and Jupyter Notebook are installed.
2. Open the Jupyter Notebook and run the main file (`projeto_credito.ipynb`).
3. The model will be trained and tested automatically.
4. After selecting the best model, it will be used to predict new customers.

## Project Structure

```
/
|-- main.ipynb             # Main notebook with all the code and analysis
|-- clientes.csv           # Initial database with customer information
|-- novos_clientes.csv     # Data of new customers for prediction
|-- README.md              # Project documentation
```

## How It Works

1. The `clientes.csv` database is loaded and analyzed.
2. Categorical data is transformed into numerical values using `LabelEncoder`.
3. The dataset is split into training and testing sets.
4. Two models are trained: Random Forest and KNN.
5. The model with the best accuracy is selected.
6. New customers in `novos_clientes.csv` are evaluated by the model.

## Author

Vinícius Vilela Novelo
