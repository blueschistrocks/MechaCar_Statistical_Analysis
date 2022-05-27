# MechaCar Statistical Analysis

## Deliverable 1 Linear Regression to Predict MPG

The dataset “MechaCar_mpg.csv” has miles per gallon (mpg) test results for 50 prototype MechaCars.  These prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle. Using my knowledge of R, I designed a linear model that predicts the mpg of MechaCar prototypes using several variables from the “MechaCar_mpg.csv” dataset.




## Statistical Summary: 

- The vehicle length, and vehicle ground clearance are statistically likely to provide non-random amounts of variance to the model. Based on the output the vehicle length and vehicle ground clearance have a significant impact on mpg on each prototype. In contrast, the spoiler angle, vehicle weight and all wheel drive (AWD) have p-Values that point to a random amount of variance within the  “MechaCar_mpg.csv” dataset.
- Since the p-Value of 5.35e-11, is much smaller than the assumed significance level of 0.05%, this indicates that there is sufficient evidence to reject our null hypothesis. This further indicates that the slope of this linear model is not zero.
- The linear model has an r-squared value of 0.7149, which indicates that approximately 71% of all the mpg predictions will be determined by this model. This further indicates that the model does effectively predict mpg of MechaCar prototypes.
- If we remove the less impactful independent variables (vehicle weight, spoiler angle, and All Wheel Drive), The predictability does decrease, but not drastically: the r-squared value falls from 0.7149 to 0.674.

