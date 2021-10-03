# MechaCar
Perform multiple linear regression analysis, collect summary statistics, run t-tests and write a summary interpretation of the findings utilizing R and R Studio. 

## Deliverable 1
## Linear Regression to Predict MPG
The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Multiple metrics, such as vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance, were collected for each vehicle. Using your knowledge of R, you’ll design a linear model that predicts the mpg of MechaCar prototypes using several variables from the MechaCar_mpg.csv file.
### Model result 
mpg = (6.267)vehicle_length + (0.0012)vehicle_weight + (0.0688)spoiler_angle + (3.546)ground_clearance + (-3.411)AWD + (-104.0)
![Resources/Images/D1_Statistical_Summary.jpg](Resources/Images/D1_Statistical_Summary.jpg)
![Resources/Images/D1_Updated_MPG.jpg](Resources/Images/D1_Updated_MPG.jpg)
## Deliverable 2

## Summary Statistics on Suspension
![Resources/Images/D2_TotalSummaryDF.jpg](Resources/Images/D2_TotalSummaryDF.jpg)
![Resources/Images/D2_Lot_Summary_DF.jpg](Resources/Images/D2_Lot_Summary_DF.jpg)

## Deliverable 3
![Resources/Images/D3_1_One_Sample_Test.jpg](Resources/Images/D3_1_One_Sample_Test.jpg)
![Resources/Images/D3_2_One_Sample_T_Test_3_Lots.jpg](Resources/Images/D3_2_One_Sample_T_Test_3_Lots.jpg)

## Deliverable 4
## Study Design: MechaCar vs. Competition
This study would involve collecting data on MechaCar and its comparable models across several different manufacturers over the last 3 years.

What are the comparable models from the competition?
Which cars will MechaCar be competing with head-to-head? which cars will be included in the study?
Which factors will look at the study to determine the relevant to selling price?

### Metrics
Collecting data for comparable models across all major manufacturers for the past few years for the following metrics:

* Safety Feature Rating: Independent Variable
* Current Price (Selling): Dependent Variable
* Drive Package : Independent Variable
* Engine (Electric, Hybrid, Gasoline / Conventional): Independent Variable
* Resale Value: Independent Variable
* Average Annual Cost of ownership (Maintenance): Independent Variable
* MPG (Gasoline Efficiency): Independent Variable

### Hypothesis: Null and Alternative
After determining which factors are key for the MechaCar's genre:

* Null Hypothesis (Ho): MechaCar is priced correctly based on its performance of key factors for its genre.
* Alternative Hypothesis (Ha): MechaCar is NOT priced correctly based on performance of key factors for its genre.

### Statistical Tests
A multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price (dependent variable); which combination has the greatest impact on price. 
