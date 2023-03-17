# Canada-Capital-Income-Time-Series-Forcast
This project is based on a time series prediction and forecasting on a Canada capital income

## About The Data:
This data is a Time-Series data with 46 Data entries. it consist of one entry per year which means that there are no month price tagg as all price has been aggregated to a year input. The data consist of two columns which is 'Date' in year form and their 'Prices'. This data has no seasonal input.

## Data Collection:
This data was gotten from Kaggle website in a CSV format and loaded in a Jupiter notebook for cleaning, EDA and Modelling.

## Data Preparation and Processing:
Data set was loaded in Jupiter for analysis. After this was done, I went further to know if datas with missing values were present in the dataset and also know the type of data it was. Date-time range was also checked to known the lenght of the data using the month frequency.

    ### Checking dataset state
   ![image](https://user-images.githubusercontent.com/124097133/225884591-ebf0f8d4-ae6c-4a59-b323-347cf99e01e5.png)
    ![image](https://user-images.githubusercontent.com/124097133/225884789-7f5d5930-e64b-4093-ad40-e2e9bfedd7ba.png)
    ![image](https://user-images.githubusercontent.com/124097133/225884934-a04a2d20-8794-43f5-83fe-2917f8620c4c.png)

## Data Visualization:
Using Exploratory Data Analysis, I visualized how price has increased and dropped over the years in Canada.
Finding the month-plot, Yearly plot and the Average of all the data input
![image](https://user-images.githubusercontent.com/124097133/225958220-3dd7da6e-bfa0-4463-ab70-27c5b881a149.png)

##  Data Modelling and Forecasting:
Linear Regression was used for data modelling as dataset was less complicated. 
Naive model was also implored to compare the performance of our Linear Model.
Data set was split into test and train data. Using the Linear Regression Model, the MAPE value gotten from test sample was 30.64% while Naive model MAPE value was gotten to be 35.79%
![image](https://user-images.githubusercontent.com/124097133/225965586-995033d6-ca8d-482f-9085-24d9945eefc9.png)
This MAPE wase not good enough as this implies that the dataset has a high Mean Absolute Percentage Error of 30% away from accuracy level. In other to rectify this, I had to fine-tune the data-set by using the Exponential Smoothing.
![image](https://user-images.githubusercontent.com/124097133/225967304-fae670c0-64eb-42ae-975c-f954c84d8604.png)
The lower and upper confidience level was calculated using the standard deviation calculated from all the yearly input. Confidience level can also be used to evaluate the accuracy of forecasting models and communicate the uncertainty associated with a forecast to stakeholders.
![image](https://user-images.githubusercontent.com/124097133/225967965-88df4034-cc1e-48b8-ace6-9c94c22adf5d.png)

## Conclusion:
  - Comparing the Mape value gotten from Naive and LInear regression, the Linear Regression performance was better.
  - After the Smoothing excercise, final MAPE forecast was gotten to be 7.03% which is a way better value.
  - During 2012 and 2013, Canada capital income reached its highest value with ranged between 40,000 - 50,000 USD before falling below 35,000 in consecutive years.
  - there are posibilities that price continues to fall as seen in the forecast.
  - ![image](https://user-images.githubusercontent.com/124097133/225883394-30d06aa1-209e-4395-abf0-3ab680c4e3b8.png)
  - This fall in price occurs as a result of
  
## Summary:
If you’re still reading to this place, congratulations on being a lover of knowledge.
With the findings from this analysis, I am certain that a lot of people will get value from it and thereafter follow the steps to carry out theirs.
Finally, Thank you for spending time reading this. It means a lot to me.
Take care of yourself, Till my next project.
