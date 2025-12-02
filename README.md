# Overview

This project presents a Bayesian analysis of factors influencing the spread of the Rosary Pea (Abrus precatorius), developed in collaboration with an Environmental Science researcher. Using a negative binomial regression framework, we modeled plant population counts as a function of environmental and anthropogenic predictors, such as human population density, precipitation, and wildfire activity. The analysis highlights how Bayesian methods provide richer uncertainty quantification—via posterior distributions, credible intervals, and model diagnostics—compared to traditional frequentist approaches. 

# The Questions

This analysis examines which predictors have a meaningful effect on Rosary Pea population counts by evaluating incidence rate ratios (IRRs) derived from the Bayesian negative binomial model. The central question is whether variables such as total human population, average precipitation, and wildfire activity significantly increase or decrease the expected plant count. By interpreting IRRs and their credible intervals, we determine which factors show evidence of influencing rosary pea abundance and the direction and magnitude of those effects.

# Tools I used

* R Studio: The development environment used to write, run, and document all analysis code in R. Below are all the libraries I used:
  
  * bayesrules: Provides accessible functions and workflows for teaching and applying Bayesian modeling concepts.

  * rstanarm: Used to fit Bayesian regression models (including the negative binomial model) using Stan’s MCMC backend.

  * tidyverse: A collection of packages for data cleaning, wrangling, and visualization (e.g., ggplot2, readr, tibble).

  * dplyr: Part of the tidyverse; used specifically for data manipulation, filtering, selecting, and summarizing.

  * readxl: Used to import data from Excel files into R.

  * broom.mixed: Helps tidy and organize Bayesian model output for easier interpretation and reporting.

  * bayesplot: Provides visualization tools for posterior distributions, diagnostics, and model checks.

  * tidybayes: Extends the tidyverse for working with posterior draws, summarizing uncertainty, and creating tidy Bayesian visualizations.

# The Data 

The dataset was collected by my collaborator and provided in a pre-cleaned format. It includes annual observations from 2005–2024 for Miami-Dade and Broward Counties in Florida. The variables consist of rosary pea population counts, the combined total human population of the two counties, a binary indicator denoting whether a wildfire occurred in a given year, and the average of the monthly mean precipitation across both counties. This dataset forms the basis for evaluating how environmental and human-driven factors influence rosary pea abundance.

# The Analysis 


# Results 


# Insights


