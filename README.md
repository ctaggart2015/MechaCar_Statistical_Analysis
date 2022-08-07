# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
The MechaCar dataset shows 50 variables for the car. We are asked to measure in r using rstudio.

### Linear Regression
<img width="693" alt="Screen Shot 2022-08-06 at 1 01 18 PM" src="https://user-images.githubusercontent.com/99035696/183258749-35780d12-d88f-46c2-871b-f3c976f592cd.png">

#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Coefficients:
(Intercept) -1.040€+02
vehicle_weight 1.245e-03
ground_clearance 3.546€+00
vehicle_length 6.267e+00
spoiler_angle 6.877e-02
AWD -3.411e+00
The vehicle length and ground clearance  that are likely to be the non-random amount of varience in the model. Those two variable sugnicantly affect the miles per gallon.

#### Is the slope of the linear model considered to be zero? Why or why not?
No it is not zero because the p value is equal to 5.35e-11.

#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model does predict the miles per hour effectvely because if we take a look at the r-squared value we can see that the value is 0.71499. Which means that aproxametly 71% is correlated to the prediction for mpg.

## Summary Statistics on Suspension Coils
In this Deliverable we use the Suspension_Coil.csv dataset to create to visuals using R to show the mean, median, variance, and standard deviation.
total_summary dataframe
<img width="1440" alt="Screen Shot 2022-08-06 at 6 01 14 PM" src="https://user-images.githubusercontent.com/99035696/183267409-fe900185-1201-4ce0-af9e-40410c8abe84.png">
<img width="846" alt="Screen Shot 2022-08-06 at 6 01 55 PM" src="https://user-images.githubusercontent.com/99035696/183267416-67ccbe71-bce4-4f8c-b17f-56a401e17eda.png">
lot_summary dataframe
<img width="1440" alt="Screen Shot 2022-08-06 at 6 02 13 PM" src="https://user-images.githubusercontent.com/99035696/183267418-0248ef55-def1-4129-99d2-3a8c404a4f0f.png">
<img width="846" alt="Screen Shot 2022-08-06 at 6 02 06 PM" src="https://user-images.githubusercontent.com/99035696/183267421-1cd6d29f-0a4f-4a2c-ae83-a85e032e8bf7.png">

#### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
I would say the majority that the current manufacturing data does meet the design specifications of not exceeding 100 pounds. If we look at the chart for the total_summary dataframe variance it tells us the number 62.29356 which is below 100pds. But when it comes to the lot_summary dataframe we can see that Lot3 is above 100 being 170.2861224 which exceeds the limits. Lot1 and Lot2 does meet specifications though.

## T-Tests on Suspension Coils
### Summary:

<img width="1440" alt="Screen Shot 2022-08-06 at 7 05 56 PM" src="https://user-images.githubusercontent.com/99035696/183268579-0a8c9e05-38b6-40a9-af4e-65278d550a8a.png">
<img width="846" alt="Screen Shot 2022-08-06 at 7 06 13 PM" src="https://user-images.githubusercontent.com/99035696/183268582-1a446478-0bda-435b-ae06-8728977378ac.png">
For the T-Tests for all of the Lots the results states that the mean of x is 1498.78. The P value looks to be 1 which above the common .05. The mean is similar to the presumed 1500.
<img width="1440" alt="Screen Shot 2022-08-06 at 7 06 41 PM" src="https://user-images.githubusercontent.com/99035696/183268586-3d151bfa-1e50-4547-b0db-1e46e58fc024.png">
<img width="846" alt="Screen Shot 2022-08-06 at 7 06 33 PM" src="https://user-images.githubusercontent.com/99035696/183268594-c2845f91-f155-46df-917d-199498f7ca32.png">
Lot1: The mean is exactly the presumed 1500. The p-value is 1.568e-11 meaning it is no statstically signifigant. 
Lot2: The mean is 1500.2. The p-value is 0.005911 which is similar to .05.
Lot3: The mean is 1496.14. The p-value is 0.1589 which is similar to the .05.

## Study Design: MechaCar vs Competition
### What metric or metrics are you going to test?
The metrics I would look into testing would be something for the type of engine and the impact on the environment. 
### What is the null hypothesis or alternative hypothesis?
The hypthoseis is based on the data from the different types of engines  would cause harm to the environment such as polution.
### What statistical test would you use to test the hypothesis? And why?
The test I would use for my hypothesis is multiple linear regression. This would show the impact on the variables from each car to the environment.
### What data is needed to run the statistical test?
The data I would have to find with the competitors and our cars would have somthing to do with the environmental impact.
