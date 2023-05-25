# CB0494
Files and materials for CCEB's Intro to Data Science and Artificial Intelligence

## Context
The project attempts to model the HDB resale prices in Singapore (taken from Singapore's Housing and Development Board). 

### EDA: Some trends, more can be seen in the ipynb notebook!  
-Resale prices over the years has increased dramatically, but the increase is not as singinificant from 2022 to 2023.
-The central region has the highest median for resale price.
-The higher a flat is located (storey range), the higher the resale price.
-Plotting was done on seaborn, matplotlib, and plotly.

### Machine Learning
-Feature Engineering techniques include ordinal encoding and target encoding using the median resale price value based on location.
-Models made include RandomForestRegressor and LinearRegression. Scoring r2 values of 0.93 and 0.69 respectively on the validation set.
