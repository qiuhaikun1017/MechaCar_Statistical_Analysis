# MechaCar_Statistical_Analysis



## Linear Regression to Predict

We have performed multi-Multiple Linear Regression on the data collected from the raw data set and test the statics importance for each individual factors: vehicle length, weight, spoiler angle, ground clearness and AWD on their impact on its mpg value. According to the below screenshot we have seen the below statics results.

![image](MechaCar_Statistical_Analysis/Screenshot/d1.png)


### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
P-value is used to test the level of statics significance and The smaller the p-value, the stronger the evidence that you should reject the null hypothesis. As there is no p-value less than 0.05 from the above 5 coefficients, thus there is no factor to provided a non-random amount of variance to the mpg values in the dataset.

### Is the slope of the linear model considered to be zero? Why or why not?
In my opinion I don’t think there is zero slope, when we look at the coefficients table, the second column: “estimate” represent the slope of linear regression. Even though they are relative small but there is no zero value.
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
R-squard is used as to present the percentage of the dependent variable variation that a linear model explains. In this case, the R-squard is 0.719, which is not a ideal high percentage but it is reasonable and not too low


## Summary Statistics on Suspension Coils


![image](MechaCar_Statistical_Analysis/Screenshot/d2_1.png)

![image](MechaCar_Statistical_Analysis/Screenshot/d2_11.png)

![image](MechaCar_Statistical_Analysis/Screenshot/d2_2.png)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
According to the below two graphs, the variance of total data ( including all Lot number) satisfy the requirement, as it is only 76.23459. The data from Lot 1 and Lot 2 satify the requirement, too. The Lot3 data exceed the requirement and is 220.01


## T-Tests on Suspension Coils
![image](MechaCar_Statistical_Analysis/Screenshot/d3_1.png)
![image](MechaCar_Statistical_Analysis/Screenshot/d3_2.png)
![image](MechaCar_Statistical_Analysis/Screenshot/d3_3.png)
![image](MechaCar_Statistical_Analysis/Screenshot/d3_4.png)

According to the above 4 graphs, we can notice that the 4 tests that we performed, based on all lot, only for lot1, only for lot2 and only for 3, all failed to reject the null hypothesis. In another words, all the p-values for the 4 test is larger than our significant level and thus the 4 samples means are similar to the population mean.


## Study Design: MechaCar vs Competition

In order to develop a strong business plan, we need to find the area of the company’s strength and weakness and find the way to differentiate from the competitor in the market. To achieve our goal, we will need to design a statics test to compare the MechaCar vehicles with other company. 
### What metric or metrics are you going to test?
I will design the test from the perspective of price competitive. I am keen to understand if the price’s mean from our sample data is significantly different from the population mean. Instead of using a specific number as we did in the deliverable 3, I would like to extract the data from a reliable source and download the data for our competitors’ price data.
### What is the null hypothesis or alternative hypothesis?
H0 : There is no statistical difference between the observed sample mean and its presumed population mean.
Ha : There is a statistical difference between the observed sample mean and its presumed population mean.

### What statistical test would you use to test the hypothesis? And why?
I will use the one sample t-test as we are comparing one sample data to the population data
What data is needed to run the statistical test?
