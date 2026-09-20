# Climate Concern and Personal Responsibility in Austria

A short empirical project using Austrian data from Round 11 of the European Social Survey (ESS).

## Research Question

**Is greater concern about climate change associated with a stronger sense of personal responsibility to reduce it?**

The project examines whether respondents who are more worried about climate change also report a stronger sense of personal responsibility to contribute to reducing it.

## Data

The analysis uses the **European Social Survey Round 11 Integrated File, Edition 4.2**, restricted to respondents from Austria.

The raw ESS data are not included in this repository. They can be downloaded from the European Social Survey Data Portal.

## Methods

The notebook includes:

- selection and cleaning of Austrian ESS11 survey data
- recoding of ESS special missing-value categories
- descriptive analysis
- weighted group means using the ESS analysis weight
- weighted regression with robust standard errors

## Tools

Python with:

- pandas
- numpy
- matplotlib
- statsmodels

## Main File

`ess11_austria_climate_concern_responsibility.ipynb`

The notebook contains the complete data preparation, analysis and interpretation.
