# Digantara-Assignment
## Table Of Content
- [Objective](#Objective)
- [Tools And Libraries](#Tools-And-Libraries)
- [Dataset](#Dataset)
- [EDA Using Python](#EDA-Using-Python)
- [Visualization Using Python](#Visualization-Using-Python)
- [Visualization Using Tableau](#Visualization-Using-Tableau)
## Objective
The objective of this assignment is to conduct a detailed analysis and visualization of the predicted conjunctions of active satellites. We will leverage a dataset that includes satellite parameters and conjunction data. The analysis will involve both general analytics for the entire dataset and specific representations for individual satellites or constellations. 
## Tools And Libraries
- Python
- Pandas
- Matplotlib
- seaborn
- Sklearn
- Tableau
## Dataset
The dataset used for this project consists of the following columns:
- NORAD_CAT_ID_1 : NORAD Catalog Number for the first object.
- OBJECT_NAME_1 : Satellite name for the first object, extracted from the CelesTrak SATCAT.
- DSE_1 : Days since epoch for the first object. This is the time in days from the epoch of the GP data used in the calculation to the calculated time of closest approach (TCA) and is an indication of how accurate the data might be at TCA.
- NORAD_CAT_ID_2 : NORAD Catalog Number for the second object.
- OBJECT_NAME_2 : Satellite name for the second object, extracted from the CelesTrak SATCAT.
- DSE_2	: Days since epoch for the second object. This is the time in days from the epoch of the GP data used in the calculation to the calculated time of closest approach (TCA) and is an indication of how accurate the data might be at TCA.
- TCA : Time of closest approach.
- TCA_RANGE : The distance or range between the two objects at TCA. Often referred to as the minimum range.
- TCA_RELATIVE_SPEED : The magnitude of the relative velocity at TCA. This value provides an indication of the risk (specific kinetic energy) for the two objects if they collided. 
- MAX_PROB : Given fixed spherical object radii and relative distance at the time of closest approach (TCA), the projected covariance ellipse is sized and oriented to produce the maximum probability.
- DILUTION : The standard deviation that produces the maximum probability defines the threshold of dilution. A smaller or larger standard deviation will produce a smaller probability.
## EDA Using Python
- Exploratory Data Analysis (EDA) is a process of describing the data by means of statistical and visualization techniques in order to bring important aspects of that data into focus for further analysis. This involves inspecting the dataset from many angles, describing & summarizing it without making any assumptions about its contents.
- In our dataset we have done data preprocessing using Python library ie, Pandas to find missing values, null values, nan values and duplicated values and found out that there is no such values in our dataset.
- Outlier finding is one of the necessary step in data preprocessing. We can find outlier using bar chart.
- In our dataset we have outliers.
- Handling outlier is the next step. We can handle it using capping method.
- This is the process of Exploratory Data Analysis (EDA).
## Visualization Using Python
- We can visualize datas using Python libraries like Matplotlib, Seaborn.
- We found Histogram of TCA Range, Histogram of TCA Relative Speed, Maxium Probability Collison, Timeline of conjunction of single satellite, total number of conjunctions occuring per day, number of conjunctions of the RSO having NORAD ID 51950 over 7 days of analysis using these libraries.
## Visualization Using Tableau
- Tableau is one of the strongest and widely used visulaization tool used for data visualization.
- We have created the Tableau interactive dashboard for Number Of conjunctions among active satellites, Conjunction data of specific satellite and Number of conjunctions occuring on specific satellite.
- The link for the interactive dashboard is https://public.tableau.com/app/profile/aravindh.a8824/viz/DIGANTARA-ASSIGNMENT/Dashboard1?publish=yes
