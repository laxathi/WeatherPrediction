# Google Colab Notebook

This repository contains a Google Colab notebook for [weather prediction].

## How to run the notebook:

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Run the cells to execute the code.
3. Make sure to install any required dependencies (e.g., `pip install pandas`).

Summary of the project WeatherPrediction
Problem Statement: Predict the weather condition (categorical classification) based on various feature as follows
**Target** variable will be **Weather**, and features will be the other columns:

Temp_C (Temperature in Celsius)
Dew Point Temp_C
Rel Hum_% (Relative Humidity in percentage)
Wind Speed_km/h
Visibility_km
Press_kPa (Pressure)
Date/Time (which is converted into temporal features like hour of the day, day of the week, etc.)

## Steps for building this classification model
1. Load and Preprocess the Data
2. Feature Engineering
3. Feature Scaling
4. Splitting the Data
5. Train the model
6. Interpret the results

**WeatherPrediction_Version2** 
## Error handling
1. ValueError: The least populated class in y has only 1 member, which is too few
   as there were some classes having only one row data which cannot be splitted to train and test data hence were dropped from the model to get the precision better.
2. Precision is ill-defined: Use zero_division parameter to control this behavior.
3. Recall is ill-defined: Use zero_division parameter to control this behavior.
The above three warnings were handled in the **WeatherPrediction_Version2**
