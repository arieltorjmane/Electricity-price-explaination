# Electricity-price-explaination

## Abstract

Every day, a multitude of factors impact the price of electricity. This chal- lenge aims to model the electricity price from weather, energy, and commercial data for two European countries - France and Germany. It is not a prediction problem, but an explanatory one, to understand the daily price variation of electricity futures contracts.

## 1 Challenge Goals
The goal is to learn a model that outputs from these explanatory variables a good estimation for the daily price variation of electricity futures contracts in France and Germany.

## 2 Data Description

Three CSV file datasets are provided: training inputs X train, training outputs Y train, and test inputs X test. The input data represents the same explana- tory variables over two different time periods.

## 2.1 Input Data
Input datasets comprise 35 columns, including:
• ID: Unique row identifier, associated with a day and a country.
• DAY ID: Day identifier.
• COUNTRY: Country identifier - DE = Germany, FR = France.
• Weather measures: Temperature, Rainfall, Wind, etc.
• Energy production measures: Natural gas, Hard coal, Hydro reser- voir, etc.
1
• Electricity use metrics: Total electricity consumption, Residual load, Net import/export, etc.

## 2.2 Output Data
Output datasets are composed of two columns:
• ID: Unique row identifier - corresponding to the input identifiers.
• TARGET: Daily price variation for futures of 24H electricity baseload.
