# covid19model
This code is the exact code that was used in Flaxman, Mishra, Gandy et al. "Estimating the effects of non-pharmaceutical interventions on COVID-19 in Europe," Nature, 2020. [https://www.nature.com/articles/s41586-020-2405-7](https://www.nature.com/articles/s41586-020-2405-7).

To run the code from the main folder in rstudio source `base-nature.r` or from terminal after reaching the root of the repository type `Rscript base-nature.r`.
The code shold be run in full mode to obtain any results. Not running full model to estimate anything is not recommended and discouraged. Only full run should be used to get results.

To get the latest versions of our progress please go to main repository and check the other releases. This folder is for the replication purposes.
# covid19modelnaturedraws
The repository with  posterior draws of the model in Flaxman, Mishra, Gandy et al. "Estimating the effects of non-pharmaceutical interventions on COVID-19 in Europe," Nature, 2020. [https://www.nature.com/articles/s41586-020-2405-7](https://www.nature.com/articles/s41586-020-2405-7) is [here](https://github.com/ImperialCollegeLondon/covid19modelnaturedraws).

# Raw data used
Data on COVID-19-attributed cases and deaths was obtained from the ECDC https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide. 

This data can be found in covid19-ecdc-data.csv.

# Posterior draws from the model
The posterior draws for all the parameters in our model can be found in the posterior-draws folder. In the folder each parameter has its own csv.
