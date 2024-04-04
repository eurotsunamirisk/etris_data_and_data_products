# Data Products for Tsunami Risk Assessment

**The tsunami data product in ETRiS (Earthquake and Tsunami Risk Information System) provides access to various PTRA (Probabilistic Tsunami Risk Assessment) components crucial for assessing tsunami risks.**
These components include *damage scales*, *fragility curves*, *consequence functions*, *vulnerability curves*, and *loss curves*.

Each folder in this repository is associated with one of the PTRA components mentioned above.

## Damage Scales
The damage scales represent an ensemble of mutually exclusive and collectively exhaustive damage states (DSi) describing the full range of possible damage for exposed assets such as buildings or other structures. The damage scale folder includes descriptions of five different damage scales found in literature.

## Fragility Curves
Fragility curves depict the probability of exceeding a given damage level (DSj) given a certain Intensity Measure (IM). The fragility curve folder contains various fragilities, available in [this table](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/fragility_curves_table.csv), with formats specified in [this document](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/Fragility_Curves/ReadMe%20file%20for%20fragility%20data.pdf). Additionally, Bayesian Model Class Selection for certain datasets is underway, indicating the posterior probability associated with each Model Class.

## Consequence Functions
Consequence functions provide the conditional probability distribution (e.g., mean and standard deviation) of a decision variable (DV), such as fatalities or economic loss, for prescribed damage states. The Consequence functions folder includes descriptions of six different functions found in literature.

## Vulnerability Curves
Vulnerability curves offer the conditional probability distribution (e.g., mean and standard deviation) of a decision variable (DV) as a function of the intensity measure (IM). The Vulnerability curve folder contains various fragilities, available in [this table](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/Vulnerability_curves_table.csv), with formats specified in [this document](https://github.com/eurotsunamirisk/etris_data_and_data_products/blob/main/etris_data_products/Fragility_Curves/ReadMe%20file%20for%20Vulnerability%20data.pdf).

## Loss Curves
Loss curves represent the mean annual rate of exceeding specific thresholds for the decision variable (DV). This section is currently in progress.
