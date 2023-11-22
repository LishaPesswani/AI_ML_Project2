# AI_ML_Project2

**OVERVIEW**
The provided dataset contains information on 426K cars to ensure processing speed. The goal is to understand what factors make a car more or less expensive. As a result of the analysis, provided recommendations to the client  as to what consumers value in a used car.

**Business Understanding**
The business understanding phase in CRISP-DM focuses on the objective or the requirement. 
In our Practical application, the objective is to help used car dealers in fine-tuning thier inventory by predicting the prices
based on the features and historic data available for those features impacting prices.

**Data Understanding**
Data Understanding has a few phases
1) Collect initial data, in this case, load the data 
2) Describe the data 
3) Explore the data, Below data has 18 columns with 4 columns as numeric and all others as Object data type
4) To check the data quality, the Below data has a lot of columns with null values which we will handle in the Data preparation phase.

**Executive summary**
This report helps understand the used car dealers about pricing dynamics. The objective of the report is to help used car dealers with the features they should be looking which might impact the car prices. And offer suggestions to fine-tune the used car inventory.

**Methodology**
Ran the analysis on the used_car vehicle data set with 426k vehicle data. Used various techniques for data cleansing and data exploration to better understand the relation of Price with other features.
1) Checked for all null values
2) For the columns with null values of more than 50 % dropped those columns along with columns that didn't add any value like id and VIN
3) Filled the remaining null values with the mode of that column
4) calculate the car_age to better understand the relation of the year with price.

Ran regression models for price prediction based on historical data.
1) Divide the data into Train and test data sets.
2) initalized the models and fit it using the train data
3) Calculatd the RSE for all and the least was for Random Forest and hence evaluated the prediction prices against that model. 

**Key Findings**
Relevant Factors: Identified several factors impacting used car prices, by using sklearn.feature_selection. The factors impacting the prices are:'Car_age', 'fuel', 'transmission', 'title_status', 'cylinders', 'drive'

The features that positively affect price increase the most are:

The year and Car_age of the vehicle: The Car_age of 3 has higher prices than the older cars . Generally, the newer and fewer miles it possesses, the more expensive it is

Vehicles with 8, 10, and 12 cylinders tend to cost more.

Missing data: A notable amount (~15%) of missing data exists in the provided dataset

**Recommendations/Conclusion**
If the goal is to get a good profit margin Inventory Optimization: Using the predictive model, dealers can estimate the proces for the cars have the inventory with the desired/profitable cars. Focus on Key Features: Based on the analysis Car_delaer should consider having the inventory with the cars having low transmission , desired fuel type and Car_age somewhere from 3-5 year as these are the desirbale models with high price range.
