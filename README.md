# Canadian Interest Rate Forecast

This project forecasts Canadian interest rates using historical data and three different models: ARIMA, Prophet, and XGBoost. The project includes data downloading, preparation, modeling, and visualization in Power BI.

## Project Structure

- **CIRF_Downloader.ipynb**: Downloads historical data for Canadian interest rates and related economic indicators.
- **CIRF_Prepare.ipynb**: Prepares the data by cleaning and structuring it for modeling.
- **CIRF_Forecast_Arima.ipynb**: Forecasts interest rates using an ARIMA model.
- **CIRF_Forecast_Prophet.ipynb**: Forecasts interest rates using the Prophet model.
- **CIRF_Forecast_XGBoost.ipynb**: Forecasts interest rates using the XGBoost model.
- **InterestRateForecast_report.pbix**: Power BI report to visualize the forecasts.

Report can be viewed here:

 https://app.powerbi.com/groups/me/reports/ab118460-fcd0-4888-a5f1-262a054b884d/fbb31a7535d4547728b7?experience=power-bi

## Prerequisites

- Python 3.8 or higher
- Power BI Desktop (for viewing/editing the report)
- Git (for cloning the repository)

## Setup Instructions

1. **Clone the Repository**:
   bash
   git clone https://github.com/your-username/Canadian-Interest-Rate-Forecast.git
   cd Canadian-Interest-Rate-Forecast

2. **Set Up a Virtual Environment (optional but recommended)**:
  bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install Dependencies**:
bash
pip install -r requirements.txt


## Download Data
Run the CIRF_Downloader.ipynb notebook to download the data. This will save bond_yield.csv canadian_economic_data.csv V39050.csv V39078.csv V39079.csv

## Prepare Data
Run the CIRF_Prepare.ipynb notebook to clean and prepare the data. This will save the prepared data to df_combined.csv.

## Run the Forecasting Models
Run CIRF_Forecast_Arima.ipynb to generate forecasts using ARIMA.
Run CIRF_Forecast_Prophet.ipynb to generate forecasts using Prophet.
Run CIRF_Forecast_XGBoost.ipynb to generate forecasts using XGBoost.
Each notebook will output forecasts for the period 2025-05-01 to 2025-10-01 and save plots/results.


## Visualize in Power BI:
Open InterestRateForecast_report.pbix in Power BI Desktop.
Update the data source to point to the files
Customize the report as needed.

License
This project is licensed under the MIT License. See the LICENSE file for details.


Copyright (c) 2025 Jonathan Liu







