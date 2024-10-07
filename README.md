## Vizualization-challenge
# Python Assignment 5 for Bootcamp

# Overview
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

# Data
1. Prepare the Data
-Import necessary packages and data.
-Merge mouse_metadata and study_results into a single DataFrame.
-Identify and remove duplicate mouse IDs with duplicate time points.
-Display the number of unique mouse IDs before and after cleaning.
2. Generate Summary Statistics
-Create a DataFrame with summary statistics for each drug regimen.
-Include mean, median, variance, standard deviation, and SEM of tumor volume.
3. Create Bar Charts and Pie Charts
-Bar Charts: Show total number of rows (Mouse ID/Timepoints) for each drug regimen.
-Create one bar chart using Pandas DataFrame.plot().
-Create another bar chart using Matplotlib’s pyplot methods.
-Pie Charts: Show distribution of unique female vs. male mice.
-Create one pie chart using Pandas DataFrame.plot().
-Create another pie chart using Matplotlib’s pyplot methods.
4. Calculate Quartiles, Find Outliers, and Create a Box Plot
-Calculate final tumor volume for each mouse in Capomulin, Ramicane, Infubinol, and Ceftamin regimens.
-Determine quartiles, IQR, and potential outliers.
-Generate a box plot for the final tumor volume distribution, highlighting outliers.
5. Create a Line Plot and a Scatter Plot
-Generate a line plot and a scatter plot to visualize the data.
6. Calculate Correlation and Regression
-Calculate the correlation coefficient between mouse weight and average tumor volume.
-Perform a linear regression analysis.

# Dependencies
To run this analysis, you will need the following Python packages:

pandas
matplotlib
scipy

# Installation
git clone https://github.com/JGraves79/Vizualization-challenge.git
cd Vizualization-challenge
Open the pymaceuticals_assignment.ipynb Jupyter Notebook.
Run the cells to perform the analysis.

# Results
The results of the analysis show the time-based results of several drug trials on mice for a fictional drug company. The information provided shows the top resulting drugs and includes a box-and-whisker chart of the final tumor size of the drugs with the best results. There is also a summary showing the linear regression and correlation of the top performing drug.

# Contributors
Contributors to this assignment included Jordan Graves, Chase Arnett, Kyle Faulkner, and Paige Manguiat.

# License
This project is licensed under the MIT License - see the LICENSE file for details.