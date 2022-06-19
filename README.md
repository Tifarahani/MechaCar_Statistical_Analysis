## MechaCar_Statistical_Analysis

#### Overview:
AutosRUs is developing a new prototype vehicle, MechaCar. MechaCar is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this project the team will:
Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
Run t-tests to determine if the manufacturing lots are statistically different from the mean population
Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers
Designed a statistical study to compare vehicle performance of MechaCar vehicles against vehicles from other manufacturers

---
#### Deliverable 1:Linear Regression to Predict MPG


<p align="center">  
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/1.png"  width="90%" height="70%">
</p>
<p align="center">  
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/1.1.png"  width="70%" height="70%">
</p>
<p align="center">  
<i>Figure 1:Linear Regression to Predict MPG</i>
</p>

---

#### Deliverable 2: Create Visualizations for the Trip Analysis
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/2.png"  width="90%" height="90%">
<p align="center">  
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/Summary1.png"  width="70%" height="70%">
</p>
<p align="center">  
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/Summary2.png"  width="70%" height="70%">
</p>


---

#### Deliverable 3:T-Tests on Suspension Coils
 
- A one-sample t-test is used to determine whether or not if PSI across all manufacturing lots was statistically different from the population mean of 1500 PSI.
The distribution of the suspension coil dataset was visualized with a density plot, which showed that the suspension coil dataset was nearly evenly distributed.
<p align="center"> 
<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/T-Test%20Suspension%20Coil.png"  width="70%" height="70%">
</p>

<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/3.png"  width="70%" height="70%">

- A t-test across all suspension coil manufacturing lots gave a p-value of 0.06 Since this is above the significance level, the two means are statistically similar.

<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/T-Test.png"  width="70%" height="70%">

- A t-test for Lot 1 gave a p-value of 1, which is above the significance level. The two means are statistically similar.

<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/Manufacturing%20Lot1.png"  width="70%" height="70%">

- The p-value for the Lot 2 t-test was 0.6072. This is above the significance level of 0.05 results in the two means being statistically similar.

<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/Manufacturing%20Lot2.png"  width="70%" height="70%">

- The calculated p-value from the Lot 3 t-test was 0.4168. This is above the 0.05 significance level and results in the means being statistically similar.

<img src="https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/img/Manufacturing%20Lot3.png"  width="70%" height="70%">

---

#### Deliverable 4: Design a Study Comparing the MechaCar to the Competition

The statistical study design has the following:
* Description of Statistical Study
* The cost of owning and maintaining a vehicle can be expensive, so AutosRUs wants to make sure their customers are getting the best value over their competitors and    would like to measure the rate of depreciation for MechaCars against other manufacturers.

#### Metric:
  Rate of depreciation (value of vehicle over time)
#### Hypothesis:
  Null hypothesis: Rate of depreciation for MechaCars is equal to their competitors
#### Alternative hypothesis:
   Rate of depreciation for MechaCars is not equal to their competitors
#### Statistical test:
  Data analysts will use multiple linear regression to predict MechaCar's rate of depreciation
* Data needed: To perform multiple linear regression to predict rate of depreciation, analysts will need vehicle values, age, and mileage.
---
#### Resources:
- R
    - Dependency
        - dplyr
- RStudio
- Datasets
    - [MechaCar_mpg.csv](https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/Resources/MechaCar_mpg.csv)
    - [Suspension_Coil.csv](https://github.com/Tifarahani/MechaCar_Statistical_Analysis/blob/main/Resources/Suspension_Coil.csv)
 
