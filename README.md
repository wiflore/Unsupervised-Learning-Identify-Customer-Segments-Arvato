# Unsupervised-Learning-Identify-Customer-Segments-Arvato
Apply unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany . 

## Project Overview
In this project, I worked with real-life data provided to Udacity by their Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. My job as a data scientist was:

* use unsupervised learning techniques to organize the general population into clusters . 
* then use those clusters to see which of them comprise the main user base for the company. 
## Project Details . 

### Step 1: Preprocessing . 
I first explored and understood the data. In this (and the next) step of the project, I worked with the general demographics data. As part of the investigation of dataset properties, I attend to a few key points:  

* How are missing or unknown values encoded in the data? Are there certain features (columns) that should be removed from the analysis because of missing data? Are there certain data points (rows) that should be treated separately from the rest?  

* Considered the level of measurement for each feature in the dataset (e.g. categorical, ordinal, numeric). What assumptions must be made in order to use each feature in the final analysis? Are there features that need to be re-encoded before they can be used? Are there additional features that can be dropped at this stage?  

I created a cleaning procedure that I applied first to the general demographic data, then later to the customers data.   

### Step 2: Feature Transformation . 

Now that the data is clean, I used dimensionality reduction techniques to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. In this stage of the project, you will attend to the following points:

* The first technique that I performed on the data was feature scaling. 
* Once I’ve scaled the features, I then applied Principal Component Analysis (PCA) to find the vectors of maximal variability to answer: How much variability in the data does each principal component capture? Can I interpret associations between original features the dataset based on the weights given on the strongest components? How many components will you keep as part of the dimensionality reduction process?  
I used the sklearn library to create objects that implement your feature scaling and PCA dimensionality reduction decisions.  

### Step 3: Clustering
Finally, in the transformed data, I applied clustering techniques to identify groups in the general demographic data. Then I applied the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company. I tackle the following points in this stage:  

* Use the k-means method to cluster the demographic data into groups. How should you make a decision on how many clusters to use?
* Apply the techniques and models that fit on the demographic data to the customers data: data cleaning, feature scaling, PCA, and k-means clustering. 
* Compare the distribution of people by cluster for the customer data to that of the general population. Can I say anything about which types of people are likely consumers for the mail-order sales company?  


## What will I need to install?
This project cannot be use as the data provided has limited use.
