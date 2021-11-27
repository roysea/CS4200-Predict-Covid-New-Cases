# CS4200-Predict-Covid-New-Cases
 This is my final project for Artificial Intelligence course. Using Neural Network model I will be predicting emergence of new cases in different locations within the US.

## Data
Coronavirus case Predictor uses the following input feature-vectors:
  - State population
  - State total area
  - State new cases/day ( historical data from: this date to this date )
  - State total Covid cases
  - State mask mandate
  - State number of fully vaccinated people (two doses or more)
  - State daily infection rate per 100 people as defined:
    - number of new cases / state population * 100
  - State daily death rate per 100 people as defined below:
    - number of new deaths / state population * 100


**Output**: New Case Count, New Death Count

## Neural Network Model
