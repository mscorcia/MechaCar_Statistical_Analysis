# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/80642682/127784594-7e18d1af-66a4-40b7-9270-a0def4426916.png)


The vehicle length and vehicle ground clearance have more of an affect on miles per gallon on the MechaCar prototype; rather than vehicle weight, spoiler angle, and All Wheel Drive.

The p-Value for this model is 5.35e-11, which is smaller than the assumed significance level of 0.05%. This shows proof to reject our null hypothesis, which indcates that the slope of this linear model is not zero.

The linear model has an r-squared value of 0.7149, which means that 71% of all mpg predictions will be determined by this model.

## Summary Statistics on Suspension Coils

### Total Lot Summary:

![image](https://user-images.githubusercontent.com/80642682/127784605-59e5c927-a787-41b1-874d-d07487537160.png)


### Individual Lot Summary:

![image](https://user-images.githubusercontent.com/80642682/127784619-f5b580a5-9f2c-4920-9d0f-9b2de4af84de.png)


Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

When observing the production lot, the variance of the coils is 62.29 PSI, which falls within the 100 PSI variance requirement.

Lot 1 and Lot 2 are within the 100 PSI variance requirement with variances of 0.98 and 7.47 respectively. Lot 3 has a larger variance of 170.29 and does not fall within the 100 PSI variance requirement. Below is a box plot illustrating my conclusion.

![image](https://user-images.githubusercontent.com/80642682/127784630-aba68569-576a-4563-9f5c-d03ed89d89f4.png)


## T-Tests on Suspension Coils

### t-test results for all lots

![image](https://user-images.githubusercontent.com/80642682/127784638-429ab4a5-4458-4bb7-9a4c-abb320ce0261.png)


The mean of the sample is 1498.78, which is the same mean in the total summary statistics above. With a p-Value of 0.06, it is higher than the common significance level of 0.05. This means that you cannot reject the null hypothesis.

### t-test results for lot 1

![image](https://user-images.githubusercontent.com/80642682/127784644-0fe5fde7-18aa-4e7c-9239-66e72caec246.png)


Since lot 1 has a p-Value of 1, we cannot reject the null hypothesis that there is no statistical difference between the observed sample mean and the presumed population mean of 1500.

### t-test results for lot 2

![image](https://user-images.githubusercontent.com/80642682/127784651-26050775-ff72-432f-886f-09f102aaad24.png)


Since lot 2 has a sample mean of 1500.02 and a p-Value of 0.61; the null hypothesis cannot be rejected, and the sample mean and the population mean of 1500 are statistically similar.

### t-test results for lot 3

![image](https://user-images.githubusercontent.com/80642682/127784656-5726f8d4-e09a-4149-9f19-f790ac8ac0ed.png)


Lot 3 has a sample mean of 1496.14 and a p-Value of 0.04, this is lower than the common significance level of 0.05. Ths means that we can reject the null hypothesis that this sample mean and the presumed population mean are not statistically different.

## Study Design: MechaCar vs Competition

This study would involve collecting data on MechaCar and its similar models across several different manufacturers for 5 years.

### Metrics
Safety Feature Rating, Current Price, Engine (Electric, Hybrid, Gasoline), and MPG

### Hypothesis: Null and Alternative
Null Hypothesis (Ho): MechaCar is priced correctly based on its performance with respect to the metrics. Alternative Hypothesis (Ha): MechaCar is not priced correctly based on its performance with respect to the metrics.

### Statistical Tests

A multiple linear regression will be used in this study.
