# Bengaluru_housing_prices_prediction


# Bengaluru House Price Prediction

This project involves predicting house prices in Bengaluru based on various features of the properties. The dataset includes information such as location, size, total square feet, number of bathrooms, and more. The goal is to build a predictive model to estimate the price of houses.

## Project Overview

The project performs the following tasks:
1. **Data Cleaning and Preprocessing**: 
   - Handling missing values
   - Converting categorical data
   - Removing outliers
2. **Feature Engineering**:
   - Creating new features like price per square foot
3. **Model Building**:
   - Using Linear Regression, Lasso, and Ridge regression models to predict house prices
4. **Evaluation**:
   - Evaluating models based on metrics such as R^2 score and accuracy
5. **Saving Cleaned Data**:
   - The cleaned dataset is saved to a CSV file for further use

## Dataset

The dataset used in this project is `Bengaluru_House_Data.csv` which includes the following columns:
- `area_type`: Type of area
- `availability`: Availability status
- `location`: Location of the property
- `size`: Size of the property in terms of BHK or Bedroom
- `society`: Society name
- `total_sqft`: Total square feet of the property
- `bath`: Number of bathrooms
- `balcony`: Number of balconies
- `price`: Price of the property

## Installation

To run this project, you need to have the following Python libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas numpy scikit-learn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Ashwadhma004/bengaluru-house-price-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd bengaluru-house-price-prediction
   ```

3. Run the Jupyter Notebook or Python script:

   ```bash
   jupyter notebook
   ```

## Data Preprocessing

- Missing values in `location`, `size`, and `bath` columns were handled using imputation.
- Categorical columns such as `location` and `size` were encoded and irrelevant columns were dropped.
- Outliers in `total_sqft` and `price_per_sqft` were removed based on statistical methods.

## Model Building

The following regression models were used:
- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**

## Evaluation

Models were evaluated using:
- **R^2 Score**: Measures how well the model explains the variability of the data.

## Results

The performance of the models will be displayed in the output of the Jupyter Notebook or Python script.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## Contact

For any questions or inquiries, please contact [gaurangchaturvedi04@gmail.com].
