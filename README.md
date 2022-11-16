# Bike-Sharing-Demand-Prediction (ML regession Project)

Problem Description
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.


Insight logo

Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)


<a href="https://www.freeiconspng.com/img/6071" title="Image from freeiconspng.com"><img src="https://www.freeiconspng.com/uploads/summary-png-icon-1.png" width="70" alt="Free Files Summary" /></a>

# ***Summary*** 
---

>The following topics were covered in this notebook:
- Downloading a real-world dataset
- Looking for null and missing values
- Try to get some insights from data
- Correlation plot
- Data Cleaning, Preprocessing and Feature engineering 
- Preparing a dataset for training
- Training and interpretation with different models
- Overfitting, hyperparameter tuning & regularization
- Predict and calculate sum evaluation metrics for model
- Model Persistence saving and loading the model
- Making predictions on single inputs and its explain it with the help of SHAP.

<br/>

<p><img alt="Insight logo" src="https://drive.google.com/uc?export=view&id=14dpaeXX-ajsM8quwe3dCCdQdrdvf29iI" align="left" hspace="20px" vspace="20px" width="45" height="60" ></p>

#**Overall Conclusion**
----
----
<br/>


* Most numbers of Bikes were rented in Summer, followed by Autumn, Spring, and Winter. May-July is the peak Bike renting Season, and Dec-Feb is the least preferred month for bike renting.
* Majority of the client in the bike rental sector belongs to the Working class. This is evident from EDA analysis where bike demand is more on weekdays, working days in Seoul.
* Temperature of 20-30 Degrees, evening time 4 pm- 8 pm,Humidity between 40%-60% are the most favorable parameters where the Bike demand is at its peak.
* Temperature, Hour of the day, Solar radiation, and Humidity are major driving factors for the Bike rent demand.
* Feature and Labels had a weak linear relationship, hence the prediction from the linear model was very low. Best predictions are obtained with a LightGBM model with an R2 Score of 0.9523 means 95.23 percente of the variance in the dependent variable that is predictable from the independent variables.
