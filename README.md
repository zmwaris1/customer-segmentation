# Customer Segmentation 
Customer Segmentation is the subdivision of a market into discrete customer groups that share similar characteristics. Customer Segmentation can be a powerful means to identify unsatisfied customer needs. Using the above data companies can then out perform the competition by developing uniquely appealing products and services.
Here the main objective  was to analyse and  identify major customer segments using        K- Means algorithm and also using different  verification method to confirm the result.
After loading the dataset I looked for duplicate values in the column. There were none. So I performed EDA. This process helped me figure out various aspects and relationships among the target and the independent variables. It gave me a better idea of which feature behaves in which manner compared to the target variable.
The dataset contains around 135080 null values in CustomerId which might tend to disturb the score so I dropped null values because of the high quantity of it.
After that I did  Feature engineering so it is the process of transforming raw data into features that better represent the underlying problem to the predictive models, resulting in improved accuracy on unseen data.
And I converted the Invoice Date column into date time format and created new features like day, day_num,  month_num, year, hours etc. From Invoice Date and again created Total Amount from Product of Quantity and Unit price columns. This can help improve machine learning accuracy since algorithms tend to have a hard time dealing with high cardinality columns.

For modelling I tried various algorithms like:
1.K-means clustering
2.Hierarchical clustering 
