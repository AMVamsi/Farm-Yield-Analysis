# Farm Yield Analysis

### SF Challenge 

#### Related to Agricutural sector

The Challenge is to identify the Parameters having impact over the Yield. The data collected from so and so company over a year from different places with different techinics  followed.

It helped in understanding how real world data affects a machine learning model. If we understand the data  given it probably increase the score of the
model that helps in predicting the yield.
 
## Resuts

When using Iterative Imputer the best fit is obtained when using the Bayesian Ridge Regressor

Data is not linearly distributed which is evident from the graphs plotted above

The model follows Gradient Boosting Regression as it has least RMSE Value and High R2 Score

### The Top 5 Features along with their scores for the output variable Yield / Acre (kilos)

* Month 218.056662
* Seed Type 18.813511
* Village 14.568921
* Pesticides used (kilos) 13.284093
* Fungicides (kilos) 3.601434

### The Top 5 Features along with their for the output variable Yield / Seed (kilos)

* Month 207.989285
* Pesticides used (kilos) 29.744753
* Fertilizers used (kilos) 19.935524
* Herbicides (kilos) 12.350891
* Acres cultivated 12.193935

### The Top 5 Features for the output variable Gross cob quantity (kilos)

* Acres cultivated 7548.562719
* Seed Used (kilos) 4121.146037
* Herbicides (kilos) 2733.122170
* Fertilizers used (kilos) 1246.494268
* Pesticides used (kilos) 1041.213936

### Top 5 Features for all the three output variables

* Month
* Seed Type
* Seed Used (kilos)
* Herbicides (kilos)
* Acres cultivated

### After normalizing the distribution and finding the Pearson's coefficient

### The output variable Yield per Acre (kilos) has a correlation with the input variables in the following order

* Fungicides (kilos) per Acre with a score of 0.11
* Fertilizers (kilos) per Acre with a score of 0.1
* Fungicides (kilos) per Seeds (kilos) with a score of 0.099
* Pesticides (kilos) per Seeds (kilos) with a score of 0.092
* Fertilizers (kilos) per Seeds (kilos) with a score of 0.087
* Pesticides (kilos) per Acre with a score of 0.086
* Herbicides (kilos) per Acre with a score of 0.017
* Herbicicdes (kilos) per Seeds (kilos) with a score 0.00062

### The output variable Yield per Seeds (kilos) has a correlation with the input variables in the following order

* Fertilizers (kilos) per Seeds (kilos) with a score of 0.31
* Herbicicdes (kilos) per Seeds (kilos) with a score 0.22
* Pesticides (kilos) per Seeds (kilos) with a score of 0.21
* Fertilizers (kilos) per Acre with a score of 0.15
* Fungicides (kilos) per Seeds (kilos) with a score of 0.13
* Fungicides (kilos) per Acre with a score of 0.12
* Pesticides (kilos) per Acre with a score of 0.093
* Herbicides (kilos) per Acre with a score of 0.032
