# Sales Data Analysis and Forecasting

## Project Overview
This project analyzes historical sales data for a retail company, identifies trends and seasonal patterns, and builds a predictive model to forecast future sales using Facebook's Prophet library. The solution is implemented in Python, focusing on data preprocessing, feature engineering, visualization, and machine learning.

---

## Features
### Part 1: Data Exploration and Cleaning
- **Load and preprocess the dataset:**
  - Handle missing values by filling them with the average for `Units_Sold` and forward filling other columns.
- **Summary Statistics:**
  - Compute mean, median, standard deviation, and frequency counts.
- **Visualizations:**
  - Time series plots for `Units_Sold` and `Revenue`.
  - Bar plots for `Units_Sold` and `Revenue` grouped by `Product_Category`.
- **Feature Engineering:**
  - Extract features such as year, month, day, and day of the week from the `Date` column.

### Part 2: Model Building and Evaluation
- **Prophet Model:**
  - Time series forecasting model trained on historical `Revenue` data.
- **Evaluation Metrics:**
  - Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
- **Visualizations:**
  - Actual vs. Predicted values with confidence intervals.
- **Predictions:**
  - Save future sales forecasts to a CSV file.

---

## Requirements
Install the necessary Python libraries using:
```bash
pip install pandas numpy matplotlib scikit-learn prophet
```

---

## Files
- **`sales_data.csv`**: Input dataset.
- **`sales_data_enriched.csv`**: Enriched dataset with additional features.
- **`sales_forecast.csv`**: Predicted future sales.
- **`Part_1_ARNAB_NAHA.ipynb`**: Jupyter Note Book for Data Exploration and Cleaning.
- **`Part_2_ARNAB_NAHA.ipynb`**: Jupyter Note Book for Model Building and Evaluation.

---

## Key Insights
1. Trends and seasonal patterns can be extracted through feature engineering and visualizations.
2. Prophet provides robust forecasting with confidence intervals, enabling future sales predictions.
3. Evaluation metrics highlight model accuracy and potential improvements.

---

## Results
- The enriched dataset and predictions are saved as CSV files for further analysis.
- Visualization plots help identify trends and model performance.

---

## Evaluation Metrics
- **Mean Squared Error (MSE)**: Measures average squared difference between actual and predicted values.
- **Mean Absolute Error (MAE)**: Captures average magnitude of prediction errors.
- **Root Mean Squared Error (RMSE)**: Square root of MSE for better interpretability.

---

## Author
Developed by Arnab Naha.
