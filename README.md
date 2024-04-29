# Bayesian estimation of a spatial-lag autocorrelation model
Bayesian estimation of a spatial-lag autocorrelation model for the diffusion of conflicts in a region near the
lake Chad in Africa in 2015. The domain of interest is subdivided in 505 cells where we observe five covariates (urbanization, number of ethnic groups, harvested area
per capita, water scarcity months and conflicts in 2014 are exogenous
variables) and the target variable for each region.

To properly model the impact of the exogenous variables on the number of conflicts in 2015 observed for each cell, we consider the spatial correlation of covariates and response variable; in other words, we include the effects of the neighboring cells in our
model since they might be very meaningful to explain the target.

## Data

`Data` folder contains the spatial dataset with the number of conflicts in 2015 and the covariates for each cell.

## Code

`Main.ipynb` contains the code to:
- Import the dataset
- Explore the spatial data
- Build the Bayesian models 
- Fit the Bayesian models
- Post processing analysis 
- Model comparisons 


## Authors
* [Matteo Tomasetto](https://github.com/MatteoTomasetto)
* [Paolo Gerosa](https://github.com/PaoloGerosa)
* [Laura Gamba](https://github.com/lauragamba)
* [Asia Salpa](https://github.com/asiasalpa)
* [Sara Tonazzi](https://github.com/saratona)
