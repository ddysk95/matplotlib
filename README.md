# matplotlib


*submission contains pymaceuticals_starter, Readme, and data folder containing data. 

* after clean up, 248 unique mouse Ids were found
* summary stats were created using the groupby and agg methods
* bar graphs created using .plot and plt.bar
* pie charts created using .plot and plt.pie
* merged chart to get final Tumor Volume for the 4 drugs in investigation
* iteratively stored tumor volume, IQR, Lower Quartile, Uper Quartile, Lower Bound, and Upper Bound for the four drug regimens
* Outliers were stored iteratively-- empy lists were removed using List comprehension to view Outlier Mouse ID
* Using the stored lists of tumor volume, a data frame was created to create the box and whisker plot
* line graph created using plt.plot 
* scatter plot creating using plt.scatter
* linear regression using y=mx+b format for the st.pearson R correlation coefficient 





* ----------------------------------
#### Observations/ Inferences

##### Only for Mouse I509, we can infer that the Capomulin treatment was generally successful in reducing tumor size. The increase near the end is a point for discrepancy/ investigation

##### Looking at the Avg Tumor Volume per weight graph and the following linear regression as well as the high correlation coefficient, one can assume Weight of the mouse is positively correlated with Average Tumor Volume. This may have been a data point that could be considered "too related" as it is easy to assume that the bigger the mouse, the bigger the tumor.

##### From the four regimens analyized in the boxplot, we can observe that Capomulin and Ramicane had the lowest final Tumor Volume with more consistent data (no outliers) than Infubinol. This may lead to more research/ confidence in Capomulin and Ramicane for lowering tumor volumes.