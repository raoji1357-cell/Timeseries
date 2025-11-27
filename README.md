# Timeseries
This dataset contains time-ordered observations used for time series forecasting. It includes a date/time column and one or more numerical variables. The data is cleaned, indexed by date, and used to analyze trends, seasonality, and generate future predictions.”

<p>The dataset contains historical exchange rate with each column representing a different currency rate over time. The first column indicates the date, and second column represent exchange rates USD to Australian Dollar.</p>
<p><strong>Part 1: Data Preparation and Exploration</strong></p>
<ol>
<li><strong>Data Loading</strong>: Load the <strong>exchange_rate.csv</strong> dataset and parse the date column appropriately.</li>
<li><strong>Initial Exploration</strong>: Plot the time series for currency to understand their trends, seasonality, and any anomalies.</li>
<li><strong>Data Preprocessing</strong>: Handle any missing values or anomalies identified during the exploration phase.</li>
</ol>
<p><strong>Part 2: Model Building - ARIMA</strong></p>
<ol>
<li><strong>Parameter Selection for ARIMA</strong>: Utilize ACF and PACF plots to estimate initial parameters (p, d, q) for the ARIMA model for one or more currency time series.</li>
<li><strong>Model Fitting</strong>: Fit the ARIMA model with the selected parameters to the preprocessed time series.</li>
<li><strong>Diagnostics</strong>: Analyze the residuals to ensure there are no patterns that might indicate model inadequacies.</li>
<li><strong>Forecasting</strong>: Perform out-of-sample forecasting and visualize the predicted values against the actual values.</li>
</ol>
<p><strong>Part 3: Model Building - Exponential Smoothing</strong></p>
<ol>
<li><strong>Model Selection</strong>: Depending on the time series characteristics, choose an appropriate Exponential Smoothing model (Simple, Holt&rsquo;s Linear, or Holt-Winters).</li>
<li><strong>Parameter Optimization</strong>: Use techniques such as grid search or AIC to find the optimal parameters for the smoothing levels and components.</li>
<li><strong>Model Fitting and Forecasting</strong>: Fit the chosen Exponential Smoothing model and forecast future values. Compare these forecasts visually with the actual data.</li>
</ol>
<p><strong>Part 4: Evaluation and Comparison</strong></p>
<ol>
<li><strong>Compute Error Metrics</strong>: Use metrics such as MAE, RMSE, and MAPE to evaluate the forecasts from both models.</li>
<li><strong>Model Comparison</strong>: Discuss the performance, advantages, and limitations of each model based on the observed results and error metrics.</li>
<li><strong>Conclusion</strong>: Summarize the findings and provide insights on which model(s) yielded the best performance for forecasting exchange rates in this dataset.</li>
</ol>
<p>Deliverables:</p>
<ul>
<li>Include visualizations and explanations for the choices and findings at each step.</li>
<li>Well-commented Python code that used to conduct the analysis and build the models.</li>
</ul>
<p>Assessment Criteria:</p>
<ul>
<li>Accuracy and completeness of the data preparation and exploration steps.</li>
<li>Justification for model selection and parameter tuning decisions.</li>
<li>Clarity and depth of the analysis in the diagnostics and model evaluation stages.</li>
</ul>
<p>This assignment offers a hands-on experience with real-world data, applying sophisticated time series forecasting methods to predict future currency exchange rates.</p>
