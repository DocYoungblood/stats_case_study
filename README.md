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
**Show a graph (pick ONE) to show our results and discuss it's relevance.
**Axis of the test. What were you testing? 
    -did we use a one tail test
    -what was the alpha
    -power
    ** basically what were our numbers



## 5 Conclusion
From our analysis, we have demonstrated our original hypothesis is invalid due to the low p_value. This supports our alternate hypothesis that at least one region has a different average fuel economy from the others. In this case the European and Asian regions showed better fuel economy. 

