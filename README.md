#  Module 5 Challenge

### Background and overview of the assignment

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.
# 
### About my code functionality 
-   **Data Preparation**: The datasets were merged, duplicates identified and removed, and the clean data was used for analysis.
-   **Summary Statistics**: Calculated and displayed for each drug regimen.
-   **Bar and Pie Charts**: Created to show treatment data and gender distribution.
-   **Quartiles, Outliers, and Box Plot**: Computed for key treatments, identifying potential outliers.
-   **Line and Scatter Plots**: Generated to visualise tumor volume over time and its relation to mouse weight.
-   **Correlation and Regression**: Calculated between mouse weight and tumor volume for the Capomulin regimen.

This comprehensive analysis provides valuable insights into the effectiveness of different drug regimens on tumor development and the relationship between tumor growth and mouse weight.

Three observations that I have made from the data have been included at the top my notebook, which can be located in the **pymaceuticals_main.ipynb** file, along with all the figures and tables generated per this assignment.
#
### References 
*Data generated by [MockarooLinks ](https://mockaroo.com/), LLC (2022). Realistic Data Generator.*

[SciPy Documentation](https://docs.scipy.org/doc/scipy/reference/)
-   Specifically, the `linregress` function from the `scipy.stats` module was used for performing linear regression.

[Matplotlib Documentation](https://matplotlib.org/stable/api/matplotlib_configuration_api.html)
- Specifically, the `flierprops` function from the `Default values and styling`  
