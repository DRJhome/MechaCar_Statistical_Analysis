# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
+ Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The angle of the spoiler, vehicle weight, and if it is AWD or not provided a non-random amount of variance. The most random variance was the two variables for ground clearance and vehicle length.
+ Is the slope of the linear model considered to be zero? Why or why not?
The slope is not considered to be zero, due to the p-value is 5.35. 
+ Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-squared value is 71% correct. I think there is other factors that were not captured in the dataset that contribute to the MPG variability of the prototypes for MechaCar
<img width="1201" alt="image" src="https://user-images.githubusercontent.com/91449005/156517955-fb5170fb-8e9d-497e-9ba4-2f8566a910d9.png">

### Suspension Coils Data
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
Lots 1 & 2 are both within design standards, Lot 3 doesn’t meet the specifications, and the variance is over 170.
T-Tests on Suspension Coils
After review of the test results for the suspension coils, all manufacturing lots shows they are not statistically different from the population median. 
Initial Test 
Lot Test 1-3
<img width="914" alt="image" src="https://user-images.githubusercontent.com/91449005/156517234-521666fb-46a3-45d9-b1e6-76a6a7e3534c.png">
<img width="872" alt="image" src="https://user-images.githubusercontent.com/91449005/156517272-0e7eaa8c-ccd4-4748-ae25-067476d06ecc.png">
<img width="890" alt="image" src="https://user-images.githubusercontent.com/91449005/156517340-928dda94-ab36-4bd7-a1c3-1bb2f91b2d12.png">

## Mechacar VS Competition
To design a study for comapring the performance of Mechacar to the competitions vehicles I would use the factors below:
+ MPG
+ Cost of maintenance
+ ride quality
I would need to use a t-test to compare datasets. I would then need to group by types of cars to compare the maintenance, MPG, and ride quality of like cars.


