# dicoding-collection
This repo showcases data analysis &amp; visualization skills learned in Dicoding's Python course. Includes EDA with Pandas/NumPy, data viz with Matplotlib/Seaborn, and building a Streamlit dashboard. Covers data cleaning, analysis, and creating interactive plots, charts, and metrics to share insights.

## Overview

This code provides a Streamlit-based dashboard for visualizing and analyzing Dicoding Collection data. It includes functionalities to filter data based on date range and displays various metrics and visualizations.

## Dependencies

- pandas
- matplotlib
- seaborn
- streamlit
- babel

## Usage

1. Clone this repository to your local system.
2. Place your cleaned data file named `all_data.csv` in the same directory as this code.
3. Run the code using Python.

## Functionality

### Data Preparation

- `create_daily_orders_df(df)`: Prepares a DataFrame for daily order counts and total revenue.
- `create_sum_order_items_df(df)`: Aggregates the quantity of each product.
- `create_bygender_df(df)`: Calculates the count of unique customers by gender.
- `create_byage_df(df)`: Calculates the count of unique customers by age group.
- `create_bystate_df(df)`: Calculates the count of unique customers by state.
- `create_rfm_df(df)`: Calculates Recency, Frequency, and Monetary values for each customer.

### Dashboard

- The dashboard allows the user to select a date range for analysis.
- Provides visualizations for:
  - Total orders and revenue over time.
  - Best and worst performing products.
  - Customer demographics (gender, age group, state).
  - Best customers based on RFM parameters (Recency, Frequency, Monetary).

## Data Loading

The code assumes that your cleaned data is stored in a file named `all_data.csv`. Ensure that the column names (`order_date`, `delivery_date`, `product_name`, `quantity_x`, `gender`, `age_group`, `state`, `customer_id`, `total_price`) are consistent with the code.

## Customization

You can customize the appearance, labels, and colors of the visualizations to suit your preferences. The code includes comments to guide you through the customization process.

Feel free to reach out if you have any questions or need further assistance!
