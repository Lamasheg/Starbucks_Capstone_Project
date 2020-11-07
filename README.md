# Starbucks_Capstone_Project
 
### Table of Contents

1. [Project Overview](#summary)
2. [Problem Statement and Approach](#Approach)
3. [Installation](#installation)
4. [Results](#results)
5. [Acknowledgements](#licensing)


    
## Project Overview<a name="summary"></a>

This project is a capstone project of Udacity's Data Science Nano Degree Program. The provided dataset is a Starbucks simulated data of customer behavior on the Starbucks rewards mobile app. 

" Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks,  someone using the app might make a purchase through the app without having received an offer or seen an offer."

## Problem Statement and Approach<a name="Approach"></a>

Generally the objective of the project is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. To tackle this exercise and find a solution to optimize Starbuck offers, I have decided to build three models to answer the following questions:

1. Will the customer return and make purchases without the need to send an offer?
2. Will the offer be successful to influence the user to complete?
3. What type of offer to send to a particular individual?

The followed approach to answer the above mentioned questions were, as follows:

1. Data understanding and exploration
2. Data wrangling and preprocessing
3. Data Analysis
4. Data Modeling 
5. Model evaluation using (Confusion Matrix, Accuracy, Recall, Precission and f1_score)

## Installation <a name="installation"></a>

- This project is developed using Python 3

- Libraries used:

    `pandas`

    `numpy`
    
    `math`
    
    `json`

    `matplotlib.pyplot`
    
    `from sklearn.ensemble import RandomForestRegressor`
    
    `from sklearn.model_selection import train_test_split`
    
    `from sklearn.neighbors import KNeighborsClassifier`
    
    `from sklearn.preprocessing import StandardScaler`
    
    `from sklearn.pipeline import Pipeline`
    
    `from sklearn.metrics import confusion_matrix`
    
    `from sklearn.metrics import accuracy_score`
    
    `from sklearn.metrics import recall_score`
    
    `from sklearn.metrics import precision_score`
    
    `from sklearn.metrics import f1_score`
            
    
## Results<a name="results"></a>

1. Most male Starbucks customer earn and average income of [30,000: 59,999], and most female customer earn high income [+90,000].
2. Starbucks mainly targets average and above_average income customer with offers.
3. Customers who earn above average income complete offers more than average income customers.
4. Most Starbucks customers are adults with ages ranging from [35: 59].
5. BOGO (buy one get one free) and discount offers are most popular across different age groups.
6. Most members joined Starbucks in 2017, further research should be carried out to understand what drove this magnitude of new customers.
7. 1% of total informational offers are successful.
8. 12% of total discount offers are successful.
9. 13% of total bogo offers are successful.
10. Female customers make more successful offer than males.
11. Generally, adults make more successful offers.
12. Total pure transactions not influinced by an offer are 18917 transactions.
13. 15% of total transactions are pure transactions not influenced by an offer.
14. Total revenue generated from pure transactions is $261236.
15. Mostly male adults earning an average level of income would make pure transactions, this segment of customers represent 6% of all adult male customers, and most of them are 58 years old.


#### I would suggest two point if improvement:

1. Trying several classification models, and choose the best one.
2. while defining the pure transaction dataset, I could have added the logic to identify transactions that were made after the period of offer influence defined in the portfolio dataset.

*Link to Medium Post:
https://lama-alshegri.medium.com/starbucks-capstone-project-an-attempt-to-optimize-offers-f8054abd8ed1



## Acknowledgements<a name="licensing"></a>
Credits go to udacity and Starbucks for providing the opportunity to practice our skills!
