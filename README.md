# MechaCar_Statistical_Analysis

## Purpose

## Summary 
### Linear Regression to Predict MPG
![Linear Regression MPG](https://user-images.githubusercontent.com/106715300/193467448-3510e357-306d-4014-aae0-e9e590ab4ae6.png)
This image shows the P-values of each variable in comparison with the MPG; it also shows the the coefficient of determination or R-squared value. The R-squared value sits at .72, this would indicate a strong correlation between MPG anf the variables given. The P-Values dig more into each individual variable in relation to MPG. Assuming a 95% confidence level, the variables that are significant: are Vehicle Length, and Ground clearance. Variables that are not significant: Vehicle weight, spoiler angle, and All wheel drive (AWD). 
The other considerations within this data, the slope is not zero, it is a significant variable in terms of P-values, and it follows a strong correlation coefficient. Because the correlation coefficient is strong, it would suggest that the current variable do a good job of predicting MechaCar prototypes. 

### Summary Statistics on Suspension Coils 
![PSI](https://user-images.githubusercontent.com/106715300/193470141-ddf05827-5899-4261-bd33-bdeb347b9d56.png)
This set of data examines the PSI mean, median, variance, and standard deviation. With these numbers the question we wanted to answer was whether or not the variance of the suspension coils exceeds 100 PSI. Before dividing by lot, it looks like the variance is fine, however upon further inspection, Lot 3 has a high rate of variance at 170, compared to the others sitting at .98 and 7.47. Lot 3 certainly exceeds the 100 PSI in allowed variance, meaning the design specification does not meet the requirements. 

### t-Tests on Suspension Coils
![PSI_tTest](https://user-images.githubusercontent.com/106715300/194179158-82aca9f7-936f-48e7-8f55-305947c5504d.png)
The t-Tests performed here show the difference in P-values based on how the lot affects the PSI for any given car, and thus a null hypothesis and alternative hypotheis are created, per the image above: alternative hypothesis: true mean is not equal to 1500. 
For Lot 1 and Lot 2, the p-values are well above the 5% confidence level, which suggests that we reject the alternate hypothesis and accept the Null. For Lot 3, the p-value sits at 4.2% which is below the 5% confidence interval, meaning we accept the alternative hypothesis. The PSI for lot 3 is outside of the normal mean. Which fits with the above conclusion. 

## Study Design: MechaCar vs Competition
### Metrics:
The most important Metrics when I look at cars are safety, gas mileage, cost, and maintaince needs. A car that needs a lot of maintainance or has a track record of falling apart quickly is not something most people want. Spending less where possible as well as spending less on gas are also important. Safety especially involving female drivers are an important factor. 
### Null and Alternative Hypothesis:
Null: MechaCar performs the same as its competition with a 95% confidence interval. 
Alternative: MechaCar does not perform the same as it competition, either better or worse. 
### Statistical test for hypothesis testing. 
I want to start with linear regression, this allows me to look at p-values for each of the variables above and decide what is significant. Then I want to use scatter plots and line of fit to ensure that variables are tested as separately as possible. Finally I want to use a two tailed t-test, to measure p-value for safety features against both car companies; specifically this test should show if MechaCar performs either better or worse compared to the competitor. 





