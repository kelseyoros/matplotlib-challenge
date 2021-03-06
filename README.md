# matplotlib-challenge

Pymaceuticals Inc. is a fictional burgeoning pharmaceutical company that specializes in anti-cancer medication. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.  Currently, the drug of interest is Capomulin.

Pymaceuticals Inc. just compiled data from their most recent 45-day animal study where 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Tumor development was observed and measured throughout the study.  With this information, I generated all of the tables and figures needed for the technical report of the study. I also provided a summary of the study results.

The tables, figures, and calculations included:

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* A bar chart that shows the number of data points per drug regimen.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/BarPlotNumDataPerDrug.JPG" width="400">


* A pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/PieChartMiceGender.JPG" width="400">

* For the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), I calculated the following:
	* The final tumor volume of each mouse 
	* The quartiles and IQR
	* Potential outliers

* A box and whisker plot with potential outliers highlighted of the final tumor volume for all four treatment regimens.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/BoxPlot.JPG" width="400">

* A line plot of time point versus tumor volume for a single mouse treated with Capomulin.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/LinePlot.JPG" width="400">

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/ScatterPlot.JPG" width="400">

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.
<img src="https://github.com/kelseyoros/matplotlib-challenge/blob/master/images/ScatterLinePlot.JPG" width="400">