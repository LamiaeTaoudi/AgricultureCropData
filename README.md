# AgricultureCropData
In this study, crop yield data collected from different farm locations in the delta region of the state of Mississippi is analyzed.
The aim is to provide predictive decisions that can help farmers increase the yield of their crops at the lowest cost.

A Geodatabase by Southern AG Services contained data collected from different farms in 5 different locations.
Yield of three crops is recorded for the year of 2020:
- Soybeans
- Corn
- Rice

Sampling information for crops yield was provided for the years: 2015, 2016, 2017, 2018, 2019, 2020
Soybeans yield for year 2020  is investigated.

ArcGIS was used to access the yield and sampling information. Using the Geoprocessing tools such as Buffer and Intersect tools, tables with averaged yield and distinct values of fertilizer nutrients at each sampling points were made.

A regression analysis is performed to study the effect of fertilizers and soil conditions on the average yield of soybeans in some farms of the Delta region.
Different Machine learning models were used to find the best model to predict the yield.
A baseline performance is created for different methods
- Linear Algorithms : Linear Regression (LR), Generalized Linear Regression (GLM), Penalized Linear Regression (GLMNET)
- Non Linear Algorithms: Support Vector Machines (SVM), Random Forest (RF)

A test harness is designed using 10-fold cross validation. 
The algorithms evaluation is done by checking RMSE and R2 metrics.
