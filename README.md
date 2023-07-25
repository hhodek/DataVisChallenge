# Data Visualization Challenge

## Description
This project focuses on analyzing and visualizing fictional data for the pharmaceutical company Pymaceuticals, Inc.

## Summary of Tasks
1. Data Preparation: The provided data files, "Mouse_metadata.csv" and "Study_results.csv," are read and merged into a single DataFrame. Duplicates for the same mouse ID and timepoint are identified and removed to create a clean DataFrame for further analysis.

2. Summary Statistics: Summary statistics for tumor volume (mean, median, variance, standard deviation, and SEM) are calculated for each drug regimen using groupby operations, resulting in a summary DataFrame.

3. Bar Charts and Pie Charts: Bar charts are generated to visualize the total number of observed mouse timepoints for each drug regimen using both Pandas and pyplot methods. Pie charts are created to display the distribution of female versus male mice in the study using both Pandas and pyplot.

4. Outliers and Box Plot: The final tumor volume for each mouse is determined for four treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The interquartile range (IQR) and potential outliers are identified, and the distribution of the final tumor volume is visualized using a box plot.

5. Line Plot and Scatter Plot: A line plot is generated to show the tumor volume over time for a single mouse treated with Capomulin. Additionally, a scatter plot is created to examine the relationship between mouse weight and average observed tumor volume for the entire Capomulin regimen.

6. Correlation and Regression: The correlation coefficient between mouse weight and average tumor volume for the Capomulin regimen is calculated. A linear regression model is performed and visualized on the scatter plot to understand the relationship between the two variables.

## Credits
Referenced class materials and ChatGPT
