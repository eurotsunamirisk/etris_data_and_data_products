## Fragility Curves
**Fragility curves** depict the probability of exceeding a given damage level (DSj) given a certain Intensity Measure (IM). The fragility curve folder contains various fragilities, available in [this table](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/fragility_curves_table.csv), with formats specified in [this document](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/Fragility_Curves/ReadMe%20file%20for%20fragility%20data.pdf). Additionally, Bayesian Model Class Selection for certain datasets is underway, indicating the posterior probability associated with each Model Class.

## Guide to accessing the empirical fragility data products:
To access the empirical fragility data for a specified Tsunami event, follow these steps:<br> 
The fragility data are stored in files named according to the following convention: **Event** **Building Class_Tsunami Name_Mk**. 
   - The term Mk defines the fragility model, where:
     - *k=1 (M1)* denotes the fragility model using a **"logit"** link function.
     - *k=2 (M2)* defines the fragility model using a **"probit"** link function.
     - *k=3 (M3)* is for the fragility model using a **"cloglog"** link function.
       
<br> These data is available in easy-to-use formats such as .csv and .xlsx.

<br> For each damage level defined as D<sub>i</sub> (″i″ defines the number of damage level), seven columns of data are provided, and this module will be repeated based on the number of damage levels. Each module contains the following columns, which are also shown schematically in the following figure: 
<br> •	**flow depth [m]:** the tsunami fragility curve employs the tsunami flow depth in meters as the measure of intensity.
<br> •	**mean-1sigma fragility:** the expected value of the fragility over the vector of fragility parameters for a given intensity minus 1 standard deviation (the lower confidence interval of the fragility)
<br> •	**mean fragility:** the expected value of the fragility over the vector of fragility parameters for a given intensity 
<br> •	**mean+1sigma fragility:** the expected value of the fragility over the vector of fragility parameters for a given intensity plus 1 standard deviation (the upper confidence interval of the fragility)
<br> •	**median:** the median (50%) of the mean fragility curve
<br> •	**logarithmic standard deviation:** the logarithmic standard deviation (dispersion) of the mean fragility curve
<br> •	**epistemic uncertainty:** epistemic uncertainty due to the uncertainty in the fragility model parameters on the median fragility
<p align="center">
  <img src="https://github.com/soltanisgeo/readme/blob/main/Fragilitygit.png" />
</p>

To rank different models based on the Bayesian Model Class selection, a csv file is provided with the name: **Bayesian Model Class Selection_ Building Class_Tsunami Name**. This file contains the posterior probability of each model M1, M2 and M3 described above.

