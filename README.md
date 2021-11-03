Claim Data Analysis
Description
Analyze simulated claims and property data and build a model that predicts claim frequency from property attributes

Abstract
 1) Preprocessing: merged different data sources (like working columns to rectify the non leap year dates)
 2) Exploration- analysis the pattern of the data for Poisson Analysis 
 3) Modelling - analytics and intercept the features using stat model(Poisson) and done final modelling with SkLearn (PoissonRegressor)

Used NegativeBinomial with exposure in glm while modelling
Deviance = 980.75
Log-Likelihood: -5942.8

Varaince looks less than mean, would have tried quasi  poisson model 

Setup Conda Environment and Launch Notebook With Conda installed, run

1) $ git clone https://github.com/mrbarun2011/Chubb.git

2) $ conda env create
3) $ source activate Chubb.

