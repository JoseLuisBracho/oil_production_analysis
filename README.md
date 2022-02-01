# Oil_Production_Analysis
Group project using Html, Tableau, and Machine Learning to tell the story and try to predict the future fluids rates of a few select oil wells, and reservoirs. 
Anaylized the history of the production of the wells and reservoirs to see the production of oil, gas, and water over time to try to predict using Machine Learning what the prduction of each well and reservoir would be for the future.

## The data
* Location data for each well
* Historical production of oil, water and gas for each well
* Historical pressures in some wells allow to build a average behaviour for each reservoir
* Petrophysical summary

## Resources used
* Excel
* Python
* Keras / TensorFlow
* Tableau

## Training the model
First a linear regression model was used with unsuccess results. Later a multilayer perceptron was used with a score of 86% which is very good in oil industry. The objective of forecast fluids production is to estimate reserves and scale the surface infrastructures.

A match between historical oil and predicted oil for the whole field is shown below:

![picture](https://github.com/JoseLuisBracho/oil_production_analysis/blob/master/oil%20page/img/oil_rate_fitting.png)

The same apply for gas an water.

## Production forecasting
Once the model reproduce the historical rate with confidence the next step is to predict fluids production. Two pictures show a dashboard for the whole field a for a particular well

### Field forecasted oil
![picture](https://github.com/JoseLuisBracho/oil_production_analysis/blob/master/oil%20page/img/Tableau_oil_field.png)
### Well BCS0032 forecasted oil
![picture](https://github.com/JoseLuisBracho/oil_production_analysis/blob/master/oil%20page/img/Tableau_oil_well.png)
