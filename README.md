# Water Potability Analysis

## Overview
This project focuses on analyzing water potability, a crucial measure of water purity. We examine various chemical parameters to determine if the water is safe for consumption.

## Platform
- **Google Colab**: Utilized for all data analysis processes.

## Data Parameters
- **Input Parameters**: pH, Hardness, Solids, Chloramines, Sulfates, Conductivity, Organic carbon, Trihalomethanes, Turbidity.
- **Output Parameter**: Potability (Indicates if the water is potable).

## Data Preprocessing
- **Cleaning**: Removed missing values.
- **Standardization**: Standardized the parameter values for uniformity.

## Analysis
- **Model Selection**: Used Gridsearch CV to identify the most effective Machine Learning model for this analysis.
- **Comparison**: Evaluated and compared the top three performing ML models based on their accuracy and efficiency in predicting water potability.
