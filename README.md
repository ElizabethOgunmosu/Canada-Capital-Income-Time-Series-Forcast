# Canada-Capital-Income-Time-Series-Forcast
This project is based on a time series prediction and forecasting on a Canada capital income

## About The Data
This data is a Time-Series data with 46 Data entries. it consist of one entry per year with means that there are no month price tagg as all price has been agregatted to a year input. the data consist of two columns which is Date in year form and their Prices. this data has no seasonal input.

## Data Collection:
This data was gotten from Kaggle website in a CSV format and loaded in a Jupiter notebook for cleaning, EDA and Modelling.

## Data Preparation and Processing:
Data set was loaded in Jupiter for analysis. After this was done, i went further to know if data were missing values in the dataset and the type of data it was. Date-time range was also checked to known the lenght of the data using the month frequency.

    ### Checking dataset state
   ![image](https://user-images.githubusercontent.com/124097133/225884591-ebf0f8d4-ae6c-4a59-b323-347cf99e01e5.png)
    ![image](https://user-images.githubusercontent.com/124097133/225884789-7f5d5930-e64b-4093-ad40-e2e9bfedd7ba.png)
    ![image](https://user-images.githubusercontent.com/124097133/225884934-a04a2d20-8794-43f5-83fe-2917f8620c4c.png)

## Data Visualization:
Using Exploratory Data Analysis, I visualized how price has increased and dropped over the years in Canada
##Data Modelling:
Linear Regression was used for data modelling as dataset was less complicated. 
Naive model was also implored to compare the performance of our Linear Model.

## Conclusion:
  - Comparing the Mape value gotten from Naive and LInear regression, the Linear Regression performance was better.
  - After the Smoothing excercise, final MAPE forecast was gotten to be 7.03% which is a way better value.
  - During 2012 and 2013, Canada capital income reached its highest value with ranged between 40,000 - 50,000 USD before falling below 35,000 in consecutive years.
  - there are posibilities that price continues to fall as seen in the forecast.
  - ![image](https://user-images.githubusercontent.com/124097133/225883394-30d06aa1-209e-4395-abf0-3ab680c4e3b8.png)
This fall in price occurs as a result of
