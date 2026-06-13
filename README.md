# New Delhi Weather Insights (2010-2023)

A time series analysis and forecasting project predicting the average daily temperature in New Delhi using historical weather data from 2010 to 2023.

## Dataset
The analysis uses the `NewDelhiWeatherInsights(2010-2023).csv` dataset, which contains daily weather metrics including Temperature, Dew Point, Humidity, Wind Speed, and Pressure.

## Project Highlights
* **Data Preprocessing:** Resampled data to a continuous daily frequency and handled missing values using linear interpolation.
* **Stationarity Check:** Conducted Augmented Dickey-Fuller (ADF) tests.
* **Modeling Techniques Evaluated:**
  * AutoARIMA with Fourier Features (SARIMAX)
  * Exponential Smoothing (ETS)
  * SARIMA
* **Best Performing Model:** AutoARIMA with Fourier Features achieved the best results with an **RMSE of 5.37** and a **MAPE of 5.56%** on the unseen test set.
* **Forecasting:** Successfully forecasted average daily temperatures for the next 365 days.

## Files
* `New_Delhi_Weather_insight.ipynb`: The main notebook containing all the data preprocessing, model training, evaluation, and visualizations.

## How to Run
1. Clone this repository.
2. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
3. Ensure you have the required libraries installed (`pandas`, `matplotlib`, `seaborn`, `pmdarima`, `statsmodels`, `scikit-learn`).
4. Upload the dataset to your working directory and run the cells.

## License
This project is licensed under the MIT License.
