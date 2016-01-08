RSV-influenza co-infection transmission in the UK

Abbreviations: RSV: Respiratory syncytial virus; IF: Influenza

This project consist of two parts. 
First, a deterministic compartmental model is developed to describe transmission of IF, RSV and co-infection between these.
Second, some of the model parameters are optimised, with a particular focus on the co-infection parameters as there is little existing data in the literature. For this, the IF and RSV parameters are optimised first individually, before the co-infection parameters are optimised.

The parameter optimisation is tested on simulated data and on a smaller data set obtained from Tanner et al. (2012, Eur J Clin Microbiol Infect Dis) that was collected at the Public Health England Laboratory in Birmingham. After this, the code is used to optimise the parameters on a larger data set from Public Health England.

This repository is divided into two main branches. One branch contains all code with seasonal forcing (i.e. all betas are a function of time) and one contains all code without seasonal forcing. The appropriate branch has to be selected first. 

Data files in each branch:

Model: This code is for the compartmental model alone with defined parameters.

Model optimisation (Simulation): This code is for the simulation of data and subsequent optimisation of the model parameters on the simulated data.

Model optimisation (Tanner et al): This code is for the optimisation of the model parameters on the data by Tanner et al.
