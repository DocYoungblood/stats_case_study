# Stats_Case_Study
## 1 Title
Fuel Economy Across Global Car Producing Regions
    Study Participants:
    Joshlyn Jamerson
    Travis Lindeman
    Austin Youngblood
    Robert (Bob) Ebend

## 2 Introduction
Our groups hypothesis is: The average fuel economy for cars from all regions(USA, Europe, and Asia) are equal. 

To better understand this we also examined the alternate hypothesis: At least one region has a different average fuel economy from the others.

We propose there is a relationship between fuel economy and the region where the vehicle was built.

## 3 Discussion of the Data
We analyzed a csv containing data of various vehicles manufactured between 1970 to 1982. The dataset was all numeric except for the car_name column which was simply the name manufacturer and model of the car in that order.

The csv file contained 398 rows, and eight columns which were:
    -mpg: Miles per gallon of vehicle
    -cylinders: The number of cylinders in this vehicle
    -displacement
    -horsepower: Horsepower of vehicle
    -weight: Weight of vehicle in pounds
    -acceleration: Acceleration in ft/s^2
    -model: Model year of the vehicle
    -origin: Country of origin (1 is the United States, 2 is Germany, and 3 is Japan)
    -car_name: Description of the car

There was some missing data in the horsepower column noted as a '?' in the dataset. The '?' value was addressed by calculating the median value for the entire column and replacing the missing '?' with the median value. This resulted in a column with complete values and replacements values that did not impact the overall outcome.

### Data Column Names Changed
We renamed the mpg column as fuel efficiency. 

To clarify the origin column, we renamed the individual regions as follows:
    1 United States (stayed the same)
    2 Germany (renamed Europe)
    3 Japan (renamed Asia)


## 4 Axis of the Test
We'll focus on the 'mpg' and 'origin' variables, as these are the variables relevant to our hypothesis. The 'mpg' variable is a numerical variable that represents the miles per gallon of the vehicles, and the 'origin' variable is a categorical variable that represents the region where the vehicles were manufactured.

## Hypothesis Testing

### These are the steps we followed for our hypothesis Testing

1. **State the hypotheses.** The null hypothesis is that the mean mpg for cars from all regions are equal, and the alternate hypothesis is that at least one region has a different mean mpg from the others.

2. **Formulate an analysis plan.** 

3. **Analyze sample data.** 

4. **Interpret the results.**

Now that we have explored the data, we can proceed to test our hypothesis. These are the steps we followed to establish and test our hypothesis. 

We will perform a one-way ANOVA test to determine whether there are significant differences in the mean mpg for cars from different regions.

For this analysis, the significance level is defined as 0.05. We analyzed the sample data with the test statistic as the F statistic, which follows an F distribution which we then plugged into Cohen's test for d. All of which facilitated the completion of the ANOVA test and allowed us to make a strong argument for our conclusion.

## Interpretation of The Results
First we looked at the data to see if there were any correlations in the data.
![Correlation Heatmap Matrix](<images/Correlation Heatmap Matrix.png>)

![Distribution of Fuel Efficiency](<images/Dist of Fuel Efficiency.png>)

Bottom line. Our finding compel us to reject our null hypothesis.
F statistic: 98.54

p value: 1.91e-35

## 5 Conclusion
From our analysis, we reject our null hypothesis. It is invalid due to the low p_value. This supports our alternate hypothesis that at least one region has a different average fuel economy from the others. In this case the European and Asian regions showed better fuel economy. 

