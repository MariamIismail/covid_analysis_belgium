# PhD_assignment_ISMAIL
Assignment for a PhD position in mathematical modelling and climate change.

## Background

The COVID-19 pandemic generated an unprecedented volume of global data. This project aims to i) explore hospitalization dynamics using an extended SIR model framework, calibrated on real-world hospitalizations. We use Bayesian optimization to maximize the likelihood of the simulated number of hopitalizations, given the observed data. ii) investigate additional variables to identify future directions for more refined modeling.

The analysis is based on data from the COVID-19 Open-DATA (COD) project, a global-scale, spatially granular dataset combining epidemiological, demographic, climate, and health system indicators.Focusing on the period 09 March 2020 to 29 June 2020, the study uses variables including  hospitalizations, age distribution, and weather/climate metrics to simulate disease dynamics and reflect on possible model extensions.

## Data

For simplicity, we restrict our analysis to Belgium, focusing on daily confirmed cases, hospitalizations, and population. Additional variables such as vaccination rates and weather are used in exploratory analysis.

## Methods
For the first of the project we used compartmentmental models and we did simple caliberation using swuared error and mainly for the parameters I used the ones indicated in the paper 
for the second part of the part we utilized posson regression to study time-sries data. 

## Results

The first SIR model was well caliberated using the squared mean error but there should be further development of the model so that we could have more accurate and good results.

For the second part, we have seen that temperature plays a signifcant role on the number of new hospitalization patients.

## Discussion

Our first SIR model could be developed
