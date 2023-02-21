![vu-anh-TiVPTYCG_3E-unsplash](https://user-images.githubusercontent.com/102637138/220366475-91d173b7-1c83-441e-a480-84fd9f1d181f.jpg)

# Poject Problem
The increase in the rate of population growth causes the need for housing to increase because it is a primary need for everyone. Currently, many companies are engaged in buying and selling land, buildings, houses, etc. Someone who wants to buy a house certainly doesn't want to buy a house at the wrong price. Real estate companies when buying houses for resale also don't want to get the wrong purchase price because it can be detrimental to the company. To set a good purchase price, an analysis of the factors that influence property prices is required. Price predictions based on location and residence specifications are also very useful for setting purchase prices. Therefore, this project created a machine learning prediction model using linear regression to help a person or company buy property at the right price.

# Project Goal
The goal of this project are:
1. Extract, explore, analyze, and visualize data
2. Make a prediction of house prices using a linear regression model
3. Imputing missing values and encoding categorical features
4. Improve model performance by reducing overfitting
5. Evaluating the prediction model using the Mean Absolute Error (MAE)

This project consists of three parts:
1. Prepare Data
    - Import
    - Explore
    - Analysis
    - Split
2. Build the Model
    - Baseline
    - Iteration
    - Evaluation
3. Communication Results
    - Testing
    
# Data Description
The dataset used has 34857 observations and 21 explanatory variables related to real estate prices in Melbourne Australia. Among the explanatory variables, there are 8 variables of type object, 12 float variables, and 1 int variable. A brief explanation of each variable is as follows:
1. Suburb = Suburb
2. Address = Addres
3. Rooms = Number of rooms
4. Type = Type br - bedroom(s); h - house, cottage, villa, semi, terrace; u - unit, duplex; t - townhouses; dev site - development site; o res - other residential.
5. Price = Price in Australian dollars
6. Method = Method: S - property sold; SP - property sold prior; PI - property passed in; PN - sold prior not disclosed; SN - sold not disclosed; NB - no bids; VB - bid vendors; W - withdrawn prior to auction; SA - sold after auction; SS - sold after auction price not ...
7. SellerG = Real Estate Agent
8. Date = Date sold
9. Distance = Distance from CBD in Kilometers
10. Postcodes = Postcodes
11. Bedroom2 = Scraped # of Bedrooms (from different source)
12. Bathroom = Number of Bathrooms
13. Car = Number of carspots
14. Landsize = Land Size in Meters
15. BuildingArea = Building Size in Metres
16. YearBuilt = Year the house was built
17. Council Area = Governing council for the area
18. Latitude = Latitude
19. Longitude = Longitude
20. Regionname = General Region (West, North West, North, North east …etc)
21. Propertycount =  Number of properties that exist in the suburbs.

# References
https://knowledgeburrow.com/what-is-high-cardinality-vs-low-cardinality/
https://statisticsbyjim.com/regression/multicollinearity-in-regression-analysis/
https://vitalflux.com/correlation-heatmap-with-seaborn-pandas/
https://machinelearningmastery.com/data-leakage-machine-learning/
https://dataschool.com/fundamentals-of-analysis/what-is-an-outlier/
https://www.kaggle.com/code/phoonyein/melbourne-houses-price-analysis-prediction
