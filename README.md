# PostDoc-CareerOutcome-Sector-Initital-Employment
Postdoctoral Career Outcomes for Life Sciences at Johns Hopkins University (Sector and Type)

The repository contains excel files with the original downloaded data and analyses of simple linear regression, multiple linear regression, and correlation. Not all values had a Gross Pay, so for the analysis some of Gross Pay columns have the same value as the the Annual Salary columns. 

# Description of Findings: 
The data showed a correlation between employment time and annual salary that is not very strong, having a value of about 0.5. The strongest correlation was actually between employment time and predicted annual salary, with a correlation of 1.0 - showing a perfect positive correlation. Meaning, the relationship between these two are strong and have a great chance of reflecting what one might actually make (despite the errors) because as one increases so does the other and vice versa. 
![](Annual%20Salary.PNG)
As you can see, the R^2 value for employment time and annual salary is relatively low at 0.2379. This tells us that the regression model accounts for about 24.0% of the variance. As we know, the more variance that is accounted for by the regression model the closer the data points will fall on the line. The variance is showing how spread out the values are from the mean. 
All independent variables for the multiple regression analysis of annual salary, predicted annual salary, and gross pay had low p-values, meaning we can reject the null hypothesis that there is no significant difference between these specified populations and our dependent variable of employed time.
In conclusion, I wanted to see the relationship between employment time and annual salary, and also employment time with other independent variables. They all showed to have a relationship. This information would be important for someone applying to work at this agency because it shows that one's predicted annual salary with time employed in the police department has a stronger linear relationship than one's actual annual salary and time employed. This would be important to know because certain police stations have great salary errors where people are predicted to make less based on their number of years working for the government but they end up making more, or they are predicted to make more and but up making less. This would be important to know when deciding which police station to work at, to make sure you are paid adequately.  
# Outline: 
Industry Question - Is there a strong relationship between time employed in the local government in the police department and annual salary or another variable?
Data Question - What data is available and what tools can be used to answer this industry question?
Data Answer - There is data found within the Baltimore City government open salary database, that has data on police salaries for this agency in the fiscal year of 2016. Regression and correlation can be done to see the relationship we want to find. 
Industry Answer - The data is able to show us multiple relationships between time of employment and salaries or gross pay. The data is able to show positive linear relationships and correlatioin between these variables. 
# Website Links:
Data Source: https://data.baltimorecity.gov/City-Government/Police-Salaries-FY2016/evsk-6ys8
Excel: https://github.com/csalley96/Police-Salaries-FY2016/blob/master/Mini%20Project%202%20(CJS).xlsx , https://github.com/csalley96/Police-Salaries-FY2016/blob/master/Original%20Data%20for%20Project%202%20(untouched).xlsx
# Simple Step-by-Step
1) Downloaded the data from the data source link above
2) I used the "Text to Columns" Data Tool to split cells and omit ones that were not needed
3) I calculated the employment time in years using the "TODAY()" command and dividing by 365
4) I calculated the slope and intercept for employment time and annual salary, and also got these values when I plotted these variables
5) I calculated the predicted annual salary using the slope and intercept found in step (4)
6) I used an IF statement to find the outliers
7) I used ToolPak to find the regression and correlation for employment time and annual salary, predicted annual salary, and gross pay. 
