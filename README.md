# AI_ML_Project2

OVERVIEW
The provided dataset contains information on 426K cars to ensure processing speed. The goal is to understand what factors make a car more or less expensive. As a result of the analysis, provided recommendations to the client  as to what consumers value in a used car.

Business Understanding
From a business perspective, we are tasked with identifying key drivers for used car prices. In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition. Reframe the task as a data task using a few sentences with the appropriate technical vocabulary.

Data Understanding
After considering the business understanding, we want to get familiar with our data. Write down some steps that you would take to get to know the dataset and identify any quality issues within. Take time to get to know the dataset and explore what information it contains and how this could be used to inform your business understanding.


Executive summary
This report helps understand the used car dealers about pricing dynamics. Objective of the report is to help used car dealers with the features they should be looking which might impact the car prices. And offer suggestions to fine tune the used car inventory.

Methodology
Ran the analysis on the used_car vechile data set with 426k vechile data . Used various techniques for data cleanisng and data exploration to better understand the relation of Price with other features. Ran regression models for price prediction based on the historical data .

Key Findings
Relevant Factors: Identified several factors impacting used car prices, by using sklearn.feature_selection . The factors impacting the prices are :'Car_age', 'fuel', 'transmission', 'title_status', 'cylinders', 'drive'

The features that positively affect price increase the most are:

The year and Car_age of the vehicle: The Car_age of 3 has higher prices than the older cars .Generally, the newer and few miles it possesses, the more expensive it is

Vehicles with 8, 10, and 12 cyclinders tend to cost more.

Missing data: A notable amount (~15%) of missing data exists in the provided dataset

Recommendations/Conclusion
If the goal is to get a good profit margin Inventory Optimization: Using the predictive model, dealers can estimate the proces for the cars have the inventory with the desired/profitable cars. Focus on Key Features: Based on the analysis Car_delaer should consider having the inventory with the cars having low transmission , desired fuel type and Car_age somewhere from 3-5 year as these are the desirbale models with high price range.
