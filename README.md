# IP-Project

## 1. Import

Contains the libraries needed for the project and the necessary code to import each table contained in the data folder

## 2. Preprocess

Contains the necessary transformations and data cleaning of the tables imported in 1. In this step a division by gender in the data was also done

## 3. Correlations

A brief analysis of how the variables correlate amongst themselves, by gender.

## 4. Gender Gap

A visual presentation of 2 proxy variables for Alcohol frequency and Alcohol quantities, represented by Alcopops and Drink_Day, by gender, in each country.
A lollipop chart was chosen for this purpose and it is ordered by thge biggest percentages in each behavior for male adolescents.

## 5. Extra variables

Processing of extra variables regarding country characteristics like PIB, percentage of population living in urban areas, etc. A correlation matrix was made to see how these new variables behave with the initial ones.

## 6. Regressions

An iterative script was made using Loops. The user can choose a variable that he wants to regress and the script runs the necessary code to show the most important variables to explain the variation of the chosen target. Then, the user can decide which variables to use or a maximum number of them and an OLS model summary is presented.

## 7. Clustering

Clustering the countries by its adolescents behaviors and characteristics (not taking into account the extra variables). The methods used were K-means, Hierarchical and Expectation–Maximization clustering.

## 8. Clustering Map 

Script for the visual and geographical representation of the clusters 

