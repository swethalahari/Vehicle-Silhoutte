# Vehicle-Silhoutte
Classifying silhouette as one of 3 different types of vehicle, using a set of features extracted from the silhouette dataset

# Approach

The data was loaded and performed statistical methods to infer the following:
The dataset has 846 rows and 19 columns
The column names has special character “.” which is replaced by “_”, to avoid error during accessing the values of the column.
The data has missing values in various columns, which were filled using the median
Also, there were outliers in the dataset, which were replaced by the 5th and 95th percentile values, instead of deleting the rows, as the number of rows are very less in the dataset.

Performed data Visualizations exploring various plots.
compared the Evaluated models(SVM) that uses all features without PCA and with-PCA applied.
Exploring GridsearchCV function 
