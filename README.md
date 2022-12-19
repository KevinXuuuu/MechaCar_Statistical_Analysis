# MechaCar_Statistical_Analysis
## Background & Purpose 
### AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG
### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
![image](https://user-images.githubusercontent.com/109333158/208361253-b2f46520-0153-4db1-a068-562b189de0dd.png)

Base on the Linear regression model above, spooiler_angle provided a non-random amount of variance to the mpg values.

### Is the slope of the linear model considered to be zero? Why or why not?
The slope of the Liner model is not considered to be zero, although it is 5.08e-08 very close to 0, but it is not 0.
0 means that thet have absoulutely no correlation between each other, but 5.08e-08 mean that they do have some kind of affect on mpg.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
No, this linear model does not predict mpg of MechaCar prototypes effectively, because it corrlation is low. 

## Summary Statistics on Suspension Coil
### Write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
![image](https://user-images.githubusercontent.com/109333158/208363073-3bdc6e34-d2cf-42d9-adb6-6d750d533c14.png)
![image](https://user-images.githubusercontent.com/109333158/208363117-4845f38f-2ff5-4766-a212-d9f853122ca0.png)

Base on total_summary and Lot_summary dataframes above, the variance is 62.29356 which is smaller than 100 pounds per square inch, the current manufacturing data meet this design specification for all manufacturing lots in total but not individually.Lot 3 failed the design specification because Lot 3 Psi is not constatnt compares to lot 2 and lot 1.

## T-Tests on Suspension Coils
### Summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
![image](https://user-images.githubusercontent.com/109333158/208363977-31897136-210b-4ce4-bd7a-f9b9058d277d.png)

Base on the t-test result, we know that 95% confidence interval is between 1497.507 and 1500.053, and the mean of x is 1498.78. In other word, it's very unlikely that x is greater than 1500. At the meantime, it provided an alternative hypothesis for us to consider, true mean is not equal to 1500.

## Study Design: MechaCar vs Competition
### Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

### In your description, address the following questions:

### What metric or metrics are you going to test?

### What is the null hypothesis or alternative hypothesis?

### What statistical test would you use to test the hypothesis? And why?

### What data is needed to run the statistical test?
