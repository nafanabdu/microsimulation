# microsimulation
This project is part of a dissertation research study focused on microsimulation modeling using the European Health Interview Survey (EHIS) 2019 as the baseline database. The simulation is conducted using R software and include a minimum of 66 simulations with 1,000 replications (which may be increased to 5,000). 
Description of the research
Title: The Impact of a Sugar-Sweetened Beverage Tax and Increased Physical Activity on the Diabetes Burden in Eastern EU Countries: A Microsimulation Model
Background
The World Health Organization (WHO) recommends implementing a 20% sugar-sweetened beverage (SSB) tax and reducing physical inactivity by 15%. (1, 2) Eastern EU countries tend to have higher sugar consumption and lower physical activity levels. (3, 4) This study aims to identify the most effective scenarios for implementing an SSB tax and physical activity (PA) programs to reduce the burden of diabetes in Eastern EU countries (based on classification of https://unstats.un.org/unsd/methodology/m49/ includes: Poland, Hungary, Czech Republic, Slovakia, Romania, and Bulgaria).
Material and Method
•	Input Parameters: Age, gender, BMI (weight, height), diabetes status, and physical activity level. These baseline parameters were derived from EHIS 2019. 
•	Synthetic Population: Created using weighted sampling to represent the real population. 
•	Microsimulation Model: A discrete event microsimulation model consisting of four states: healthy, obesity, diabetes mellitus (DM), and deceased. The model runs annually from 2020 to 2050. 
•	Outcome Measure: Prevented incidence of DM from 2020 to 2050. 
•	Model Validation: Cross-validation using MAPE/MAE and RMSE. 
•	Sensitivity Analysis: Conducted using Monte Carlo simulations with 1,000 iterations to provide a 95% uncertainty interval (UI). 
•	Comparative Scenarios: Different scenarios will be analyzed to assess the effects of various interventions:
-	Baseline Scenario: No intervention 
-	Counterfactual Scenario: SSB Tax 20% + PA increase 15% 
-	Comparator Scenarios: 
1)	SSB Tax 10% 
2)	SSB Tax 10% + PA 10% 
3)	SSB Tax 10% + PA 15% 
4)	SSB Tax 10% + PA 20% 
5)	SSB Tax 20% 
6)	SSB Tax 20% + PA 10% 
7)	SSB Tax 20% + PA 20% 
8)	PA 10% 
9)	PA 15% 
10)	PA 20% 
