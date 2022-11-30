# Customer Segmentation 
Customer Segmentation is the subdivision of a market into discrete customer groups that share similar characteristics. Customer Segmentation can be a powerful means to identify unsatisfied customer needs.<br> Using the above data companies can then out perform the competition by developing uniquely appealing products and services.
Here the main objective  was to analyse and  identify major customer segments using        K- Means algorithm and also using different  verification method to confirm the result.<br>

# EDA:<br>

1. After loading the dataset I looked for duplicate values in the column. There were none. So I performed EDA.<br> 
2. This process helped me figure out various aspects and relationships among the target and the independent variables. It gave me a better idea of which feature behaves in which manner compared to the target variable.<br>
3. The dataset contains around 135080 null values in CustomerId which might tend to disturb the score so I dropped null values because of the high quantity of it.<br>

# Feature Engineering<br>

1. After that I did  Feature engineering so it is the process of transforming raw data into features that better represent the underlying problem to the predictive models, resulting in improved accuracy on unseen data.<br>
2. And I converted the Invoice Date column into date time format and created new features like day, day_num,  month_num, year, hours etc.<br>
3. From Invoice Date and again created Total Amount from Product of Quantity and Unit price columns.<br>

## This can help improve machine learning accuracy since algorithms tend to have a hard time dealing with high cardinality columns.

# Modelling:<br>

For modelling I tried various algorithms like:<br>
1.K-means clustering<br>
2.Hierarchical clustering<br>

# Tools Used:<br>

<img src="https://github.com/zmwaris1/logos/blob/main/png-clipart-scikit-learn-python-scikit-logo-brand-learning-text-computer.png" alt="sickit-learn" height="40" style="vertical-align:top; margin:4px"><img src="https://github.com/zmwaris1/logos/blob/main/tutorial_matplotlib.png" alt="matplotlib" height="40" style="vertical-align:top; margin:4px"><img src="https://github.com/zmwaris1/logos/blob/main/Pandas_logo.svg.png" alt="Pandas" height="40" style="vertical-align:top; margin:4px">
<img src="https://github.com/zmwaris1/logos/blob/main/105040771-43887300-5a88-11eb-9f01-bee100b9ef22.png" alt="Numpy" height="40" style="vertical-align:top; margin:4px"><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" alt="Python" height="40" style="vertical-align:top; margin:4px">

# Conclusion:<br>
Upon plotting the WCSS(Within Cluster Sum of Squared Errors) vs k(number of clusters) plot the optimal number of "k" turns out to be 2. This is used in the final result to present the segment of customers based on the given data.

## Thank you for visiting.
