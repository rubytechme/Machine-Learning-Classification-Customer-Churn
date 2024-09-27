# Machine-Learning-Classification-Customer-Churn

## Introduction:
Customers, they say, are the lifeblood of every business. I conducted a comprehensive analysis of customer churn, developing a predictive model that empowers businesses to proactively identify at-risk customers and implement targeted retention strategies. By leveraging this model, organisations can significantly reduce churn rates, increase customer lifetime value, and ultimately enhance long-term profitability.

This data is an open source data and was pooled from an open source platform. You can find data [here](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset?select=customer_churn_dataset-training-master.csv)

## Skills/ concepts demonstrated:
The following capabilities that were incorporated-
- Hyper parameter Tuning
- Optimization technique
- Machine learning
- Exploratory Data Analysis
- Feature Engineering 
- Onehot encoder
- Pipeline
- Defining Functions
- Oversampling 

## Libraries Used:
- Pandas
- Seaborn
- Sklearn
- Matplotlib

## Models Evaluated:
- Super Vector Machine
- Decision Tree Classifier
- Random Forest Classifier


## Documentation
- We had major cases of customer churning, showing a case that 249,999 customers churned and 190,833 had not churned.

- All the variables showed a less than 50% correlation with each other. However, when including churn in the correlation plot, it showed that support calls given to customers had a correlation to the churn

- To increase sales, the company should consider hiring more salespersons in regions with high sales potential, such as California. Also, by conducting a deeper analysis to identify the specific factors driving sales in California, the company can implement similar strategies in other locations to achieve similar growth.

- For the customers who churned, there was no significant difference in the distribution of subscription types, indicating that no particular subscription type was more prone to churn than others.

- I also check for the balance ration of the data to be sure that the model will not be overfitting any class. The balance ratio was 0.76. This is fair, and can also imply that there is a minority class. However, I did not oversample. An evaluation dataset can be brought in to see if predictions for unseen data will not be biassed.

- It also showed that the ages of the customers was one of the important variables used in predicting the churn. It means that there's a statistically significant relationship between a customer's age and their likelihood of churning. And this could be as a result of:

  1. Age-based segmentation: Customers of certain age groups may be more likely to churn due to factors such as life stage, preferences, or financial circumstances.
  2. Product-age fit: Older customers may be less likely to adapt to new product features or changes, leading to churn.

- The best parameters for the random classifier model were max_depth:None, min_samples_split:10, n_estimators:150. Which improved the model by a small margin

- Among all 3 models that I used, Decision Tree gave the best performance for the model as opposed to other models that were used like the Super vector machine(SVM), and random classifier.

- See all code and documentation [here](https://github.com/rubytechme/Machine-Learning-Classification-Customer-Churn/blob/main/CustomerChurn_comb.ipynb)
