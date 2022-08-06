# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
The MechaCar dataset shows 50 variables for the car. We are asked to measure in r using rstudio.
### Linear Regression
<img width="693" alt="Screen Shot 2022-08-06 at 1 01 18 PM" src="https://user-images.githubusercontent.com/99035696/183258749-35780d12-d88f-46c2-871b-f3c976f592cd.png">
### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Coefficients:
(Intercept) -1.040€+02
vehicle_weight 1.245e-03
ground_clearance 3.546€+00
vehicle_length 6.267e+00
spoiler_angle 6.877e-02
AWD -3.411e+00
The vehicle length and ground clearance  that are likely to be the non-random amount of varience in the model. Those two variable sugnicantly affect the miles per gallon.
### Is the slope of the linear model considered to be zero? Why or why not?
No it is not zero because the p value is equal to 5.35e-11.
### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The linear model does predict the miles per hour effectvely because if we take a look at the r-squared value we can see that the value is 0.71499. Which means that aproxametly 71% is correlated to the prediction for mpg.
