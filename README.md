# TOTVS_solution
churn prediction using  simple sklearn algorithms

My answers to questions:
Question 1
1) Predicting customer churn using suprevised learning algoritms - seems to be the main purpose of this dataset
2) Customer segmentation by and LTV analysis 
3) Segmentation of sellers by unit price/total price/quantity/loyality

Question 2
Churn analysis seems to be more important and valuable for the business. Building ML models, which predict customer churcn by their behaviour can help us to detect loyal clients and build an ongoing relationships with them for a long time. Also turn advertising to clients with high churn probability.

Question 3 see .ipynb file
Validated accuracty for non-churn clinets detection is 99,89%
For churn clients 98,96%
This was achieved by using Gradient Boosting classifier from sklearn package

Question 4
Dataset contains many categorial variables with simple encoding. So, application of logistic regression and knn alghorithms failed to make predictive models.
Practically, tree alghoritms (as decision trees, random forest and Gradient Boosting) showed their efficiency with so-called "dummy encoded" variables.  Also tree-containg algoritms has at least 2 tunable hyperparameters. 
We choosed maximum tree depth and leaf nodes to tune. 

If i had more time i would continue tuning of hyperparameters in GBC algoritm. But I also need more data :)

