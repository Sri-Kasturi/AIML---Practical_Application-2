# AIML---Practical_Application-2
## Business Context
To explore the used cars daraset and identify the key features/attributes that determine the price of a used car. The goal then is to provide clear recommendations to the car dealership company's on what makes a car more or less expensive.

## Data framework and Analysis -
I have used the CRISP-DM framework to analyze the data and below are the set of steps that I have followed to analyze the data -
1. Data understanding - Load the data. The data has 426K records of used cars with numeric and categorical features.
2. Data cleansing and pre-processing -Data imputation tenchniques to identify missing and irrelevant data columns - drop columns, deelete null values, fill in null values with most frequent data values, label encoder to get dummy values for categorical columns, quartiles to detect outliers and filter the data. I then used Exploratory Data Analysis (EDA) to visualize data accurately and identify important features for data preprocessing and model selection.
3. Data pre-processing - Used Correlation heatmaps to identify the key features that determine the price of a car i.e., year, odometer, cylinders, drive, fuel type. 
4. Model selection - Explored Linear regression, Ridge, Lasso, and SFS to analyze the performance of each of the models against the features. I then ran the assessment to compare whch of these models had the optimal performance i.e., least RMSE and higher accuracy%.
5. Evaluation - Overall assessment of the models have confirmed that the Ridge CV has the optimal performance in terms of accuracy%.
   
## Hi-level findings and observations -
1. Year of manufacturing ahs a strong positive correlation with the price. Cars that were manufactured in the last 5 years had the highest price. Older the car, lesser the price. Most cars that were manufactured between 2000-2020 were available in the market. 
2. Odomter is another key attribute which has a negative correlation i.e., the less miles the car has travelled, the higher the price. 
3. Cars that have automatic are priced higher than cars that are manual type.
4. Diesel cars are priced higher than other fuel types 
5. V8 cars have more selling price than cars with other count of cylinders

## Recommendations and next steps
Based on the above data insights, cars with years of manufactruing <5 with lower odometer use, automatic transmission are expensive. Additionally, cars with 4wd drive, and V8 tend to also be expensive. These observations provide valuable information for developing future  strategies for further exploration.

## Next steps -
At the moment, I have used only 3 of the model selection methods, but expanding the scope to additional ML models would help optimize the accuracy% in predicting the price of a car. Also, Further analysis of the data with a broader set could be very beneficial i.e., getting additional source data on used car sales from other venues (outside of used car dealerships) would shed light on current market trends, customer demands, and competitior analysis. 
### Link to the GitHub repository Pyton Notebook can be found here - https://github.com/Sri-Kasturi/AIML---Practical_Application-2/blob/main/Practical%20Application%20_2_Sri_Kasturi.ipynb
