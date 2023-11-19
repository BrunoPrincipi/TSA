# Forecasting Future Trends: A Time Series Analysis of Retail Sales in New Zealand

![image](https://github.com/BrunoPrincipi/TSA/assets/125404145/5ce40940-7bfc-474b-973e-93f7f305b193)

# Project Overview
Welcome to my time series forecasting project, inspired by the practical insights gained from the book "Time Series Forecasting in Python." Here, I apply the knowledge acquired from the book to predict retail sales trends in New Zealand over the next two years.
By implementing Python-based techniques recommended in the book, I aim to actively utilize and demonstrate the acquired skills. The specific focus is on forecasting retail sales, utilizing Stats NZ data and following the step-by-step approach outlined in the book written by Marco Peixeiro.
Book: Peixeiro, Marco. Time Series Forecasting in Python. Manning Publications, 2022.

# Project Structure
The project is structured with the following sections:

* Import Libraries: Set up necessary tools for analysis.

* Load the Data: Acquire the quarterly retail sales dataset.

* Data Preprocessing:	Clean and prepare the data.

* Inspect and Visualize:	Explore and visualize dataset characteristics.

  * Identifying Seasonal Patterns:	Analyze for recurring patterns, especially seasonality.

* Baseline Model:	Establish a baseline for performance reference.

  * Predictions and MAPE:	Generate initial predictions and calculate MAPE.

* SARIMA Model:	Implement SARIMA with ADF test for stationarity.

  * Train and Test Sets:	Divide data for model validation.

  * Optimize SARIMA Function:	Fine-tune parameters for optimal performance.

  * Run Optimized Function and Residual Analysis:	Apply optimized SARIMA function and analyze residuals.

  * Predictions and MAPE:	Generate SARIMA predictions and calculate MAPE.

  * Forecast into the Future:	Extend SARIMA predictions for future trends.

* LSTM RNN Model:	Implement LSTM Recurrent Neural Network.

  * Scale the Data and Data Windowing:	Scale data and apply windowing for LSTM.

  * Building and Fitting the Model:	Construct and train the LSTM model.

  * Predictions and MAPE:	Generate LSTM predictions and calculate MAPE.

  * Forecast into the Future:	Extend LSTM predictions for future trends.

* Conclusions:	Summarize findings and insights.

  * MAPE Comparison and Final Predictions:Compare MAPE values between SARIMA and LSTM models and present final 
predictions.

# Technologies Used
* Python
* Scikit-learn
* Keras
* Pandas
* NumPy
* Statsmodels
* Plotly
* Matplotlib

# Goals and Results

##  Goals:

* Understanding Time Series Data: Gain insights into the characteristics of time series data, including patterns, seasonality, and sequential dependencies.

* Application of Time Series Models: Implement SARIMA and LSTM models to forecast future values based on historical time series data.

* Experimentation and Learning: Embrace an iterative learning process by experimenting with various models, adjusting parameters, and addressing challenges encountered during the project.

* Portfolio Development: Create a comprehensive portfolio piece demonstrating my ability to handle time series data, apply forecasting models, and effectively communicate findings.

##  Results:

In summary, this time series forecasting project focused on predicting quarterly retail sales with a dataset consisting of 112 data points. The univariate nature of the data revealed a clear seasonality trend, with peak sales occurring in the second quarters.
Three models—SARIMA 1, SARIMA 2, and LSTM—were deployed to capture and forecast sales patterns. SARIMA 1, with an order of (2,1,3),(0,1,1,4), demonstrated a Mean Absolute Error (MAPE) of %2,4. SARIMA 2, with an order of (1,1,0),(2,1,2,4), exhibited a lower MAPE of %0,95. The LSTM model, configured with a sequential architecture, showed a slightly higher MAPE between %3-5.
While SARIMA models did well in catching the seasonal trends, it's good to note that LSTM models usually work better with larger datasets, around 10,000 or more points. Still, its inclusion in the analysis served the purpose of experimentation, learning, and comparison.
In conclusion, SARIMA models performed better here, but including LSTM allowed us to see how it stacks up in a scenario where it's not ideal. This comparison helps us understand which models might work best based on the data we have. Further tweaking and exploring different models could improve predictions, especially with more extensive datasets.



# Files

# TO DO

# Contact Details
