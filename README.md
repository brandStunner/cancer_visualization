# (Dataset Exploration Title)
## by (Rutherford Kofi Brandful)


## Dataset

> The Breast Cancer (Wisconsin) Diagnosis dataset contains the diagnosis and a set of 30 features describing the characteristics of the cell nuclei present in the digitized image of a of a fine needle aspirate (FNA) of a breast mass. Data was obtained from kaggle, and cleaned by dropping some columns which had no bearings on analysis. Having overall cleaned data of rows 604, the dataset had two categorical and 30 numerical variables.


## Summary of Findings

> The data had only one categorical variables, by name diagnosis, which had three different values. I looked at how this categorical variable trended by diving deep into how it trends over the various numerical measurement variables like radius, perimeter, area and compactness.
For the presentation, I narrowed the insight to how radius,area,perimeter and compactness tell about a particular cell.
Then I followed it up with pairplots to see how they compared when plotted when plotted agaist other variables,then moved on with heatmaps to show how some of the variables are related. I made use of different colours of the pairplots to make distinction of the different cells in this plot.


## Key Insights for Presentation

> The countplot revealed that there were 212 counts of malignant cancer cell types, making up 35.1% of the total cell. Pre-malignant cells were the least, having 34 cells, which constituted just 5.6% of the total cell. Benign cells had the most count, totaling 358 count and represented 59.3% of the total cells.

> The radius, perimeter, area and compactness of the dataset have a significant degree of correlation with one another suggesting multicollinearity.

> The radius_mean,area_mean,perimeter_mean and compactness_mean had a general trend that, benign cells had smaller values of these variables, whiles malignant cells had larger values of measurements. This trend was spotted easily by the pairplot. Even though there were few outliers which did not follow this triend, it did not invalidate this observation.

> The pre-malignant had very random trend with no particlur pattern. As observed in the pointplot, they generaly had wide range of values between the lower and upper boundary measurement of radius,area,perimeter and compactness. 

