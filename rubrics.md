# Rubrics-F&B: “It’s friday night!”

## Data Preprocess

    %(2 Points) Demonstrated how to properly do data aggregation.
        Do you need to aggregate/summarise the number of visitors before doing time series padding?
        Do you need to filter the time to certain hours after doing time series padding?
        Do you need to replace NA value?
    %(2 Points) Demonstrated how to properly do time series padding.
        Should you do time series padding?
        Do you need to round the datetime into hour or minutes?
        When is the start and the end of the time interval for time series padding?

## Seasonality Analysis

    (2 Points) Compared multiple time series decomposition approach.
        Can you decompose the time series into the observed data, trend, hourly seasonality, weekly seasonality, and the residuals?
    (2 Points) Reported interpretable hourly and weekly seasonality.
        Can you create a better visualization of hourly and weekly seasonality?
        How do you interpret the seasonality? Describe the interpretation.

## Model Fitting and Evaluation

    (4 Points) Demonstrated how to prepare cross-validation data for this case.
        Do you need to do cross validation before doing time series analysis?
        How do you split the data into training and testing dataset?
    (4 Points) Demonstrated how to properly do model fitting and evaluation.
        What data preprocessing you used before fitting the model?
        What time series model did you use?
        Can you visualize the actual vs estimated number of visitors?
        how to evaluate the model performance?
    (4 Points) Compared multiple model specifications.
        How many forecasting model will you use?
        Will you use exponential smoothing? Will you use ARIMA?
        How to evaluate the model performance?
        Can you visualize the actual vs estimated number of visitors?

## Prediction Performance

    (6 Points) Reached MAE < 6 in (your own) validation dataset.
    (6 Points) Reached MAE < 6 in test dataset.

## Conclusion

    (4 Point) Assumption Checking
        Does the model meet the autocorrelation assumption?
        What about the normality of residuals?
        If the assumptions are not met, what is the cause? how to handle that?
        Based on seasonality when the highest visitors ?
