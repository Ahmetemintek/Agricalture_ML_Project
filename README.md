# Business Overview

The prediction in the agriculture dataset is to conclude whether the crop will be healthy, damaged by pesticides or damaged for other reasons at the end of the harvest season. <br/>

Before we start this prediction, there are elements that we must consider. Various factors such as crop damage, soil fertility, rodents, beneficial chemicals, and nature. Most of these are reasons beyond our control, but the amount and time of use of the pesticide is a variable that can be controlled. When the dose of pesticide is too high, it can spoil the whole crop, so it is important to make sure that it is used in sufficient quantities. The data in the agriculture dataset belong to the products obtained by some farmers at the end of the harvest season.

# Data Overview

It was determined that the data shape consists of 88858 observations and 10 features. There are 9000 missing values in the data. The data set consists of integers, float and objects. Since we want to predict the cause of the damage to the crop, the target class is crop damage. There are 3 different types of data in the target class. 0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides.

The data has been taken from an online source that is Kaggle. Data's source information is in the references section.

# Tasks

1.	Exploratory Data Analysis <br/>
2.	Visualisation <br/>
3.	Feature Engineering <br/>
4.	PCA <br/>
5.	Machine Learning Model <br/>

# Data Dictionary

Estimated_Insects_Count:  Estimated insects count per square meter <br/>
Crop_Type: Category of Crop (0,1) <br/>
Soil_Type: Category of Soil (0,1) <br/>
Pesticide_Use_Category: Type of pesticides uses (1- Never, 2-Previously Used, 3-Currently Using) <br/>
Number_Doses_Week: Number of doses per week <br/>
Number_Weeks_Used: Number of weeks used <br/>
Number_Weeks_Quit: Number of weeks quit <br/>
Season: Season Category (1,2,3) <br/>
Crop_Damage: Crop Damage Category (0=alive, 1=Damage due to other causes, 2=Damage due to Pesticides)

