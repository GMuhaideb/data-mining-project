# Forecasting and Analyzing Industrial Production in Saudi Arabia

This repository serves as a practical implementation of data mining concepts for the purpose of Forecasting and Analyzing Industrial Production in Saudi Arabia. It is a fulfillment of our data mining course, where we explore the utilization of Matplotlib, Anaconda, and Python to gain insights into economic trends.

## Forecasting Economic Dependency Ratio using ARIMA Model

In this project, we focus on forecasting the economic dependency ratio using the ARIMA (AutoRegressive Integrated Moving Average) model. The ARIMA model is a powerful tool for time series forecasting, particularly suitable for predicting economic indicators over specific time periods.

Here's how we accomplished the ARIMA model implementation:

1. We initiated the process by importing the data using the `pd.read_csv()` function.

2. The 'Time Period' column was converted into a datetime format and assigned as the DataFrame index. The DataFrame was then sorted in ascending order based on the index.

3. For the ARIMA model, we chose an order of (p, d, q) as (1, 1, 1), indicating one autoregressive term, one differencing term, and one moving average term.

4. The model was fitted to the data, enabling it to capture the underlying patterns.

5. To obtain forecasted values and confidence ranges, we specified a forecast period of five quarters using the `get_forecast()` method.

6. The forecasted values were extracted, and a new index was generated based on the last index of the original data.

7. The generated forecasted values were printed for inspection.

8. Leveraging the Matplotlib library, we plotted both the economic dependency ratio data and the forecasted values on a graph for visualization.

## Getting Started

To replicate this project and delve into the world of forecasting and analyzing industrial production, follow these steps:

1. Clone this repository to your local machine.
2. Install Anaconda and set up your Python environment.
3. Install the required dependencies using the provided `Economic dependency ratio_data` csv file.
4. Run the provided Python script to execute the ARIMA model and visualize the results.

Feel free to explore the code and adapt it to your specific needs. This project serves as a valuable learning experience in the realm of data mining and time series forecasting.

Happy forecasting!


