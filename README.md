# Dimensionality-reduction-using-PCA-and-tSNE

## Context ##

In this case study, we will use a dataset that contains various socio-economic attributes for countries around the world.  

## Objective ##

The objective of this problem is to reduce the number of features by using dimensionality reduction techniques such as PCA and t-SNE, and extract insights about the data.

## Data dictionary ##
The data has the following attributes:

- country: Name of the country
- child_mort: Death of children under 5 years of age per 1000 live births
- exports - Exports in % of the GDP per capita
- health - The total spend on health given as % of GDP
- imports - The value of imports given as % of GDP per capita
- income - The net income per person
- inflation - Inflation rate %
- life_expec - Average life expectancy in years
- total_fer - The fertility rate - Average children per woman in the country
- gdpp - GDP per capita

## Methodolgy
Principal Component Analysis (PCA) and Stochastic Neighbor Embedding was used.

## Results
A. There are three groups in the data. Each group has a different set of characteristics:

- Group 1 (green) represents countries with the highest income and exports of all. Also, they have a high gdpp and life expectation. Their mortality child rate is low as well as the imports. Also they seem not to invest to much in health programs. **Group 1 seems to be the richest countries with no too much goverment intervention**.

- **Group 2 (orange) represents developed countries with strong social programs**. This countries have high income but not as much as the group 1. Gdpp is the highest, the lowest inflation, very high life expectation and also the lowest child mortality rate.  

- **Group 3 (blue) represents undeveloped and poor countries**. This countries have a high child mortality, high fertility rate, their imports are high because they don't produce much. In the other hand they have a low income, exports and gdpp.

B. Calculations are in Caseof study_PCA_tSNE.ipynb
