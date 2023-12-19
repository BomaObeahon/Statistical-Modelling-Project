# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Develop a statistical model aimed at extracting insights regarding the correlation between the number of bikes in a selected city and the attributes of noteworthy places within that area.
## Process
1.Establish a connection to the Citybikes API and analyze its structure to extract Bike Station latitude, longitude, and the count of bikes for a specified location.
2.Connect to the Foursquare API and investigate its structure to obtain information about restaurants and bars corresponding to each bike station identified.
3.Establish a connection to the Yelp API and explore its structure to gather details about restaurants and bars associated with each bike station .
4.Joining the all 3 DataFrame into 1 DataFrame,using the merge method.
5. Creating visuals for the DataFrame using the data visualization libraries in python.
6.Creating an SQLite database to store the information in the DataFrame.
7.Creating a regression model to illustrate the relationship between the number of bikes and the points of interest in the selected location.


## Results
R-squared is a measure of how well the independent variables explain the variability of the dependent variable. In this case, the R-squared is 0.056, indicating that the model explains 5.6% of the variability in the number of bikes.
The coefficients represent the estimated impact of each independent variable on the dependent variable. For example, the coefficient for "const" is -1.397e+04, suggesting a negative impact on the number of bikes.
The P-values associated with each coefficient test the null hypothesis that the corresponding coefficient is equal to zero. If the P-value is less than the significance level (often 0.05), the null hypothesis is rejected. In this case the p-value is 0.
## Challenges 
I struggled with extracting data from the json file in the api request.
## Future Goals
1. Study more on api request and json files.
2. Explore more modelling types.
