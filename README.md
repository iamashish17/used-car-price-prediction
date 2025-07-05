# Used Car Price Prediction

This project predicts the selling price of used cars using machine learning.

## How it works

- The data is cleaned and prepared from a CSV file of car details.
- A Linear Regression model is trained on features like brand, year, kilometers driven, fuel type, and more.
- You can input details of a car, and the model will predict its selling price.

## How to use

1. Open the `Untitled1.ipynb` notebook in Jupyter.
2. Run all the cells to load the data, train the model, and make predictions.
3. To predict a price, enter the car's details in the format shown in the notebook.

## Requirements

- Python 3
- pandas
- numpy
- scikit-learn

Install requirements with:
```bash
pip install pandas numpy scikit-learn
```

## Dataset

The dataset (`Cardetails.csv`) includes columns like:
- name, year, selling_price, km_driven, fuel, seller_type, transmission, owner, mileage, engine, max_power, seats
