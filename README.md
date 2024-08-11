# Predicting National Energy Consumption: A Comprehensive Multi-Forecasting Approach

## Description

This project aims to predict national energy consumption for various countries over the next five years using a comprehensive multi-forecasting approach. The notebook leverages historical energy consumption data and applies three forecasting models—ARIMA, Prophet, and Darts—to evaluate their performance and determine the most effective method for future predictions.

### Key Features:
- **Data Source**: Historical energy consumption data.
- **Forecasting Models**:
  - **ARIMA**: A classical time series model for capturing temporal dependencies.
  - **Prophet**: Developed by Facebook, designed to handle seasonality and holidays.
  - **Darts**: A modern library that supports a range of models including neural networks.

## Installation

To set up the project environment, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
2. **Create a Virtual Environment (optional but recommended):**
   ```bash
    python -m venv env
    source env/bin/activate   # On Windows use: env\Scripts\activate
3. **Install Dependencies:**
   Ensure you have the required libraries. Install them using:
   ```bash
    pip install -r requirements.txt

## Usage

1. **Open the Notebook:**
   Open the notebook in Google Colab or Jupyter Notebook:
   [Open Notebook](https://colab.research.google.com/drive/1wLqVN8o9G5opUd996jLOxpXdlQ7v6vMb?usp=sharing)

2. **Run the Cells:**
   Execute each cell in the notebook sequentially to perform the following:
   - **Load and preprocess the data**: Import and clean historical energy consumption data.
   - **Apply Forecasting Models**:
     - **ARIMA Model**: Generate forecasts using the ARIMA model.
     - **Prophet Model**: Forecast energy consumption using the Prophet model, accounting for seasonality and holidays.
     - **Darts Model**: Apply various models from the Darts library for forecasting.
   - **Generate forecasts and evaluate model performance**: Compare model forecasts and evaluate their accuracy using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

3. **View Results:**
   The notebook provides forecasts and performance metrics, including MAE and RMSE. Results and visualizations will be displayed directly in the notebook.

## Results

The notebook will output:
- **Forecasted Energy Consumption Values**: Predictions for energy consumption over the next five years.
- **Comparative Analysis**: Evaluation of ARIMA, Prophet, and Darts models to determine the most effective forecasting method.
- **Performance Metrics**: Includes Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) for each model to assess their accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the creators of ARIMA, Prophet, and Darts for their contributions to time series forecasting.




