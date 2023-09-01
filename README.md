# Forecasting Border Immigration into the United States using the ARIMA Model


Welcome to the **Border Immigration Forecasting Project**! This repository contains code and resources to analyze and forecast the rate of immigration into the United States through its neighboring borders. We'll be using the ARIMA (AutoRegressive Integrated Moving Average) model to analyze historical immigration data and predict the rate of migration for the next five years.

## About the Dataset

The dataset in this project contains comprehensive information about border immigration into the United States from January 1996 to March 2019. It includes details such as:

- Port Name
- State
- Port Code
- Border
- Date
- Measure (Method) of Migration
- Value (Number) of Migrants
- Location

## Project Goals

The main objectives of this project are:

1. **Trend Analysis:** Analyze historical immigration data to identify trends and patterns in the rate of migration across different borders.
2. **ARIMA Modeling:** Implement the ARIMA model to forecast the future rate of immigration based on historical trends.
3. **Five-Year Forecast:** Use the trained ARIMA model to predict the rate of migration for the next five years.
4. **Insights and Visualization:** Visualize the historical and forecasted immigration data to provide insights into migration patterns.

## Getting Started

To use the code and reproduce the analysis, follow these steps:

1. Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/your-username/border-immigration-forecast.git
   ```

2. Navigate to the project directory:

   ```bash
   cd border-immigration-forecast
   ```

3. Install the required dependencies. You might want to set up a virtual environment first:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks:

   - `1_data_preparation.ipynb`: Preprocess and explore the dataset.
   - `2_arima_modeling.ipynb`: Build and evaluate the ARIMA model.
   - `3_forecasting.ipynb`: Use the trained model for forecasting and visualize the results.

## Contributions

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Acknowledgments

I would like to express my gratitude to the creators of the dataset for providing valuable immigration data. This project would not be possible without their efforts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

I hope you find this project informative and useful for understanding and predicting border immigration trends into the United States. Happy forecasting!
