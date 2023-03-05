# COVID-19 Forecasting Dashboard

This repository contains the code and data for a Tableau dashboard that forecasts COVID-19 cases based on flight frequency, population density, and active cases using an LSTM model.

## Getting Started

To get started with the dashboard, we collected the following data from various sources:
* flight_data: A dataset containing flight frequency data for each country
* population_density_data: A dataset containing population density data for each country
* corona_data: A dataset containing COVID-19 case data for each country


## Building the LSTM Model

To build the LSTM model, we followed these steps:
1. Data preprocessing: We combined the flight frequency, population density, and COVID-19 case data into a single dataset and performed feature scaling to normalize the data.
2. Train-test split: We split the data into training and testing sets using an 80-20 split.
3. Building the model: We built an LSTM model using the Dart model.
4. Training the model: We trained the model on the training data for 100 epochs using a batch size of 32.
5. Evaluating the model: We evaluated the model on the testing data using the mean squared error (MSE) and the root mean squared error (RMSE) metrics.

## Building the Tableau Dashboard

To build the Tableau dashboard, we followed these steps:
1. Connecting to the data: We connected to the flight frequency, population density, and COVID-19 case data using Tableau's data connection feature.
2. Preparing the data: We joined the three datasets together using a common country code and performed some data cleaning to remove any missing or invalid values.
3. Creating the visualizations: We created several visualizations to show the relationship between flight frequency, population density, and COVID-19 cases and used a line chart to show the LSTM model's predictions for each country.
4. Publishing the dashboard: We published the dashboard to Tableau Server so that others can access it and interact with the data.

The data and code I cannot allow to publish publicly, however, the project handbook is available for reference. 

## Conclusion

In this project, we built a Tableau dashboard that forecasts COVID-19 cases based on flight frequency, population density, and active cases using an LSTM model. We hope this dashboard will be useful for researchers and policymakers in understanding the spread of COVID-19 and making informed decisions about public health interventions.

