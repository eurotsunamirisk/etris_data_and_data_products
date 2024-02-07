## Guide to accessing the empirical fragility data results:
This guide explains how to access the empirical fragility data for the specified Tsunami event in easy-to-use .csv and .xlsx formats. <br> i) The fragility data are stored in files, each named as follows: **Building Class_Tsunami** **Name_Mk.** The term Mk defines the fragility model, where *k=1* *(M1)* denotes the fragility model using **"logit"** link function, *k=2* *(M2)* defines the fragility model using **"probit"** link function, and *k=3* *(M3)* is for the fragility model using **"cloglog"** link function. 
<br> For each damage level defined as D<sub>i</sub> (″i″ defines the number of damage level), seven columns of data are provided, and this module will be repeated based on the number of damage levels. Each module contains the following columns, which are also shown schematically in the following figure 
<br>
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

