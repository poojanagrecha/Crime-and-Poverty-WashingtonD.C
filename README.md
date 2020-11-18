

# Project: The Correlation of Crime and Poverty in Washington D.C.
![image](https://github.com/poojanagrecha/Crime_vs_Poverty_Analysis/blob/master/Images/Screen%20Shot%202020-11-18%20at%2010.59.31%20AM.png)

The purpose of this analysis is to carefully examine and evaluate the impact of poverty on crime. Washington D.C. was chosen as a model city for the study. Data was collected from two datasets ([Poverty.csv](https://github.com/poojanagrecha/Crime_vs_Poverty_Analysis/blob/master/Resources/ACS_2017_Poverty_Status_Variables_Tract.csv) and [Crime.csv](https://github.com/poojanagrecha/Crime_vs_Poverty_Analysis/blob/master/Resources/AnyConv.com__Crime_Incidents_in_2017.csv)) that show the amount of crime and the level of poverty during the year 2017. For this data, Washington D.C. is broken up into 179 Census Tracts. 
## Exploratory Data Analysis

Prior to merging the two datasets, we took some time to explore them individually. The poverty dataset had many columns breaking the Total Population up into ‘above’ or ‘below’ the poverty line and then into age segments to include < 6, 6-11, 12-17, 18-59, 60-74, 75-84, and 85+. Since we were under tight time constraints, we elected to simplify this down to Population Below the Poverty Line, Child Population Below the Poverty Line, and the Total Population; all of these were broken down into rows of the 179 Census Tracts.

![bottom10image](https://github.com/poojanagrecha/Crime-and-Poverty-WashingtonD.C/blob/master/Images/Percent%20Population%20Below%20Poverty%20Line%20by%20Census%20Tract%20-%20Bottom%2010.png)
- Percentage of Population Below Poverty Line by Census Tract- Bottom 10 

![top10image](https://github.com/poojanagrecha/Crime-and-Poverty-WashingtonD.C/blob/master/Images/Percent%20Population%20Below%20Poverty%20Line%20by%20Census%20Tract%20-%20Top%2010%20-%20Final.png)
- Percentage of Population Below Poverty Line by Census Tract- Top 10 

## Does a higher population affect total crime?

Incidence of crime is more concentrated around the city center which has a higher population.

![image](https://github.com/poojanagrecha/Crime_vs_Poverty_Analysis/blob/master/Images/GMap_HeatMap_Washington%20Crime.png)

## Will a higher percentage of poverty mean more crime occurence in a specific area?

A regression analysis was used to quantify the relationship between the total population of poverty to the number of crimes. The accuracy of the model in Figure 10. is mildly relevant. The data shows a weak uphill positive linear relationship with an R squared value of 0.82.


 
