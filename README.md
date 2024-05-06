# Cost-of-Living-in-the-United-States
## Objective 
To enhance public awareness regarding the cost of living in the United States, enabling individuals to make informed decisions concerning their expenditures.
## Data
The data set comprises information on the following parameters:
- State
- County
- Family member count
- Income
- Various expenses

Files: 

The complete data details can be found [here](https://www.kaggle.com/datasets/asaniczka/us-cost-of-living-dataset-3171-counties/data).

Moreover, provided is the [shapefile](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A6/6.3/us-states.json) used for the geospatial analysis.

Lastly, included is the [time series analysis](https://fred.stlouisfed.org/series/USACPALTT01CTGYM) file.

Tableau Storyboard:

The results of the analysis can be seen [here](https://public.tableau.com/app/profile/suzan.diab/viz/CostofLivinginUnitedStates/CostofLiving).

- Only the steps relevant to the final analysis are displayed.

- More comprehensive findings can be seen in the Jupyter notebooks.

## Research Questions
1) Do higher housing expenses correlate with increased spending on other items compared to those with lower housing costs?
2) What states have the highest/lowest overall cost of living?
3) What counties have the highest/lowest overall cost of living?
4) How does the number of dependents impact different expenses?

## Data Cleaning Procedures
- Dropped unnecessary columns
- Changed data types of certain columns
- Renamed columns for easier viewing
- Checked for missing values and duplicates
- Split the family member count column into separate columns
- Replaced criteria in the parent status column 

## Tools
For this project, the following python libraries were used:
- pandas & numpy - for data analysis
- seaborn, matplotlib, sklearn, and folium - for data visualization 
## Code
The code is available as Jupyter Notebooks and can be found inside the scripts folder.
