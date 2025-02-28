# fuel-cpi-correlation
# Fuel Prices Analysis in Nairobi, Kenya

## Project Overview

This project analyzes fuel prices and their relationship with economic indicators like the Consumer Price Index (CPI) in Nairobi, Kenya. It uses historical data to identify trends and correlations, aiming to provide insights into the dynamics of fuel price fluctuations and their potential impact on the local economy.

## Data Source

The project utilizes a CSV file named `fuel_prices_nairobi.csv` containing historical data on fuel prices (Super Petrol, Diesel, Kerosene), CPI metrics (overall CPI, Transport CPI, Energy CPI), exchange rates, and Murban Crude oil prices. This data is assumed to be collected from reliable sources and spans a specific period (e.g., February 2024 to February 2025).

## Methodology

1. **Data Loading and Preprocessing:** The code loads the data from the CSV file using the Pandas library and converts the 'Date' column to datetime format.

2. **Visualization:** Matplotlib is used to create line graphs visualizing the trends of fuel prices, CPI metrics, exchange rates, and Murban crude oil prices over time.

3. **Correlation Analysis:** The code calculates the correlation matrix between fuel prices, CPI metrics, and other relevant factors to identify potential relationships.

4. **Regression Modeling:** A linear regression model is built to explore the relationship between fuel prices and CPI, predicting the impact of fuel price changes on CPI.

## Observations and Explanations

- **Fuel Price Trends:** Visual analysis of the fuel price trends reveals fluctuations over time, potentially influenced by global oil prices, local policies, and economic conditions.

- **CPI Correlations:** The correlation analysis highlights potential relationships between fuel prices and CPI metrics, suggesting that fuel price changes can influence overall inflation and specific sectors like transportation and energy.

- **Regression Insights:** The linear regression model provides a quantitative estimate of the impact of fuel price changes on CPI, allowing for predictions and policy considerations.

- **Exchange Rate and Murban Crude:** The visualization and analysis of exchange rates and Murban crude oil prices provide context for understanding the global factors influencing fuel prices in Nairobi.

## Potential Applications

- **Economic Monitoring:** This analysis can be used to monitor fuel price trends and their impact on the local economy.

- **Policy Recommendations:** The insights gained can inform policy decisions related to fuel price regulation, subsidies, and inflation control.

- **Consumer Awareness:** The findings can help consumers understand the factors influencing fuel prices and make informed decisions.

## Further Research

This project can be extended by:

- Incorporating additional data sources, such as global oil market data, local economic indicators, and government policies.

- Exploring more complex models to forecast fuel price trends and their economic impact.

- Developing interactive visualizations and dashboards to facilitate data exploration and communication.


## Repository Contents

- `fuel_prices_nairobi.csv`: The dataset used for analysis.
- `fuel_prices_analysis.ipynb`: Jupyter notebook containing the Python code for data loading, processing, visualization, and modeling.
- `README.md`: This file, providing an overview of the project.
- `fuel_prices_vs_cpi_corrected.png`: Plot showing the relationship between Fuel Prices and CPI.
- `exchange_rate_vs_crude.png`: Plot illustrating Exchange Rate vs. Murban Crude prices.

## Getting Started

To run this project:

1. Clone the repository: `git clone https://github.com/kyosloth/fuel-prices-nairobi.git`
2. Install the required libraries: `pip install pandas matplotlib sklearn`
3. Open and run the `fuel_prices_analysis.ipynb` notebook using Jupyter Notebook or Google Colab.

## Contributing

Contributions and suggestions for improvements are welcome. Please feel free to open issues or pull requests.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
