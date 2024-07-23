# Pymaceuticals Inc. Analysis
This repository contains a comprehensive analysis of tumor volume data from Pymaceuticals Inc. The analysis includes data cleaning, summary statistics, visualization, and correlation analysis.

## Dependencies and Setup
* Python 3.x
* matplotlib for visualization
* pandas for data manipulation
* scipy for statistical analysis
* numpy for numerical computations
## Data Files
- mouse_metadata.csv: metadata for mice used in the study
- study_results.csv: study results data
## Analysis Overview
The analysis consists of the following components:

Data Cleaning: merging mouse metadata and study results data, handling duplicates, and creating a clean DataFrame.

Summary Statistics: calculating mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

Visualization: generating bar plots, pie charts, box plots, line plots, and scatter plots to visualize the data.

Correlation and Regression: calculating the correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen.

## Results
The analysis reveals that Capomulin and Ramicane are more effective in reducing final tumor volume compared to Infubinol and Ceftamin. Mouse r944 treated with Capomulin shows an initial increase in tumor volume before decreasing to its lowest point on the 35th day. There is a strong direct relationship between mouse weight and average tumor volume, with a correlation coefficient of 0.84.

## Future Directions
Investigate the underlying mechanisms driving the initial increase in tumor volume in response to Capomulin treatment.
Explore the effects of Infubinol's outlier on the overall treatment outcome.
Analyze the relationship between mouse weight and tumor volume in the context of other treatments to identify potential patterns or differences.
