# Canadian Interest Rate Forecast

This project forecasts Canadian interest rates using historical data and three different models: ARIMA, Prophet, and XGBoost. The project includes data downloading, preparation, modeling, and visualization in Power BI.

## Project Structure

- **CIRF_Downloader.ipynb**: Downloads historical data for Canadian interest rates and related economic indicators.
- **CIRF_Prepare.ipynb**: Prepares the data by cleaning and structuring it for modeling.
- **CIRF_Forecast_Arima.ipynb**: Forecasts interest rates using an ARIMA model.
- **CIRF_Forecast_Prophet.ipynb**: Forecasts interest rates using the Prophet model.
- **CIRF_Forecast_XGBoost.ipynb**: Forecasts interest rates using the XGBoost model.
- **InterestRateForecast_report.pbix**: Power BI report to visualize the forecasts.
- **data/**: Contains raw and prepared data files.
  - `raw_data.csv`: Placeholder for downloaded data.
  - `prepared_data.csv`: Placeholder for prepared data.

## Prerequisites

- Python 3.8 or higher
- Power BI Desktop (for viewing/editing the report)
- Git (for cloning the repository)

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Canadian-Interest-Rate-Forecast.git
   cd Canadian-Interest-Rate-Forecast
