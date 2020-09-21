# Wine-not? (hehe)

Analysis of wine quality data (presented by [Penn State Eberly College of Science](https://online.stat.psu.edu/stat508/lesson/analysis-wine-quality-data)) with Python.

### Analysis of Wine Quality Data

*In the second example of data mining for knowledge discovery, we consider a set of observations on a number of red and white wine varieties involving their chemical properties and ranking by tasters. Wine industry shows a recent growth spurt as social drinking is on the rise. The price of wine depends on a rather abstract concept of wine appreciation by wine tasters, opinion among whom may have a high degree of variability. Pricing of wine depends on such a volatile factor to some extent. Another key factor in wine certification and quality assessment is physicochemical tests which are laboratory-based and takes into account factors like acidity, pH level, the presence of sugar and other chemical properties. For the wine market, it would be of interest if human quality of tasting can be related to the chemical properties of wine so that certification and quality assessment and assurance process is more controlled.*

*Two datasets are available of which one dataset is on red wine and have 1599 different varieties and the other is on white wine and have 4898 varieties. Only white wine data is analyzed. All wines are produced in a particular area of Portugal. Data are collected on 12 different properties of the wines one of which is Quality, based on sensory data, and the rest are on chemical properties of the wines including density, acidity, alcohol content etc. All chemical properties of wines are continuous variables. Quality is an ordinal variable with a possible ranking from 1 (worst) to 10 (best). Each variety of wine is tasted by three independent tasters and the final rank assigned is the median rank given by the tasters.*

### Objective of the Analysis

*Prediction of Quality ranking from the chemical properties of the wines*

*A predictive model developed on this data is expected to provide guidance to vineyards regarding quality and price expected on their produce without heavy reliance on the volatility of wine tasters.*

### Data

Penn State provides three data files, all of which are saved within this repo in "datasets". I only used the "Wine_data.xlsx" file for all of my analysis (because I'm lazy).

Access these files directly from Penn State here:

* [Wine_data.xlsx](https://online.stat.psu.edu/onlinecourses/sites/stat508/files/Wine_data.xlsx)
* [Training50_dataset.csv](https://online.stat.psu.edu/onlinecourses/sites/stat508/files/Training50_winedata.csv)
* [Test50_dataset.csv](https://online.stat.psu.edu/onlinecourses/sites/stat508/files/Test50_winedata.csv)

### Analytical Approaches

I applied the following to the wine data:

1. Linear Regression
2. Polynomial Regression
3. Decision Tree Classification
4. Random Forest Classification
5. K-Nearest Neighbors Classification
