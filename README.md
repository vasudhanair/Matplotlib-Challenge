# Matplotlib-Study-Result-Visualizations

This study explores a pharmaceutical research dataset(of Pymaceuticals.Inc) to compare the performance of the drug "Capomulin" versus other treatment regimens for squamous cell carcinoma (SCC), a commonly occuring form of skin cancer. A series of visualizations using Matplotlib to prove or disprove Capomulin's effectiveness were created.
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 
45 days, tumor development was observed and measured. 

Dependencies and Libraries

* Python

* Matplotlib

* Pandas

* Scipy

* Numpy

Study was carried out with the following action items listed below

1. The data was checked for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

2. A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was generated.

3. A bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of total mice for each treatment regimen throughout the course of the study was generated.

4. A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study was generated

5. The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin was calculated . Also, the quartiles and IQR were calculated and quantitatively determined if there were any potential outliers across all four treatment regimens.

6. A mouse that was treated with Capomulin was selected and a line plot of tumor volume vs. time point for that mouse was generated.

7. A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen was generated.

8. The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot was calculated.

9. Here are the following three observations that can be made from the data.
Observations and Insights

a) The bar graph depicted that the Drug regimen capomulin has the maximum number of mice at 230 and the drug Zoniferol has the smaller mice number at 182.The total mice count by gender showed that there were 124 females and 125 males.The removal of duplicates resulted in mice count being 248.

b) The correlation between mouse weight and average tumor volume is 0.84. There is a positive correlation , with an increase in average tumor volume when there is an increase in mouse weight.

c) The regression analysis helps us understand how much the average tumor volume(dependent variable) changes when the weight of mice (independent variable) changes. The r-squared value of 0.70 suggests that the model fits the data to 70%. Higher R-squared values represent smaller differences between the observed data, and the fitted value. 70% the model explains all of the variation in the response variable around its mean. Among the drugs in the Drug regimen, Capomulin and Ramicane are the most effective as they reduce the size of tumors most as compared to others.
