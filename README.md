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
