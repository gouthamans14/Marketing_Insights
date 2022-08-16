# Marketing_Insights
End to End Marketing Data Analytics involving: RFM, Value Based and K MEANS Segmentations. Two Customer Classifier models One to Classify  Value based Customers and another one to predict customer retention. Cohort Analysis and Cross selling recommendations.


Project Name: Marketing Insights For E-Commerce Company

Data: Given data is in excel files.

I have also merged them to create one dataframe->Merged_Data. 

Also did Data Munging to create Customer 360 data -> Customer_df1.csv

Notebooks:

1) Start with Marketing Insights where I had done general EDA. Data Munging to create required DataFrame for further detail analysis.
    This notebook also Involves Heuristic Segmentation ie RFM segementation and Data Profiling based on it.
    Included Marketing Strategies according to the customer Type. 


2) KMeans-Segmentation.ipynb -> This notebook contains Scientific Segmentation Method ie K means segementation and Data Profiling is done 
based on that.

3) Customer_ Classifier.ipynb -> Segmented Data in a value based manner to categorize customer, did some feature engineering and 
Built a general model for classification of customer based on value.
 
    Did some data preprocessing to find the Retention customers and built a classifier to predict customer return frequency 

4) Cohort analysis -> Created Monthly Cohorts. Found cohort based Insights like retention, quantitiy sold, revenue generated etc.
Constructed heatmaps for better understanding

5) Cross Selling -> Used apriori Algorithm to generate rules for recommendation
