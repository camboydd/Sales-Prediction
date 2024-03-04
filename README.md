# Sales Prediction with Machine Learning

This script demonstrates a machine learning approach to predict sales based on provided sales data. It utilizes various preprocessing techniques, feature engineering, and two different regression models: Linear Regression and Random Forest Regression.

## Requirements

Before running the script, ensure you have the following dependencies installed:

- Python 3.x
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using pip:

```
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage

1. **Data Preparation**: Replace the placeholder 'sales_data.csv' with the path to your sales data CSV file.

2. **Understanding the Data**: The script begins by loading the sales data and displaying its initial rows to get an understanding of the data structure.

3. **Feature Engineering**: Several new features are created from the existing data, such as total price, order month, order year, etc., to enhance the predictive power of the model.

4. **Data Visualization**: The script visualizes the distribution of sales using boxplots before and after removing outliers to understand the data's characteristics better.

5. **Data Preprocessing**: Unnecessary columns are dropped, missing values are handled, and categorical variables are encoded for machine learning models.

6. **Model Training and Evaluation**:
   - Linear Regression: The script trains a Linear Regression model and evaluates its performance using Mean Squared Error and R^2 Score.
   - Random Forest Regression: Similarly, a Random Forest Regression model is trained and evaluated.

7. **Visualization**: The script visualizes the density of true vs predicted sales using joint plots for both models to assess the model's performance visually.
