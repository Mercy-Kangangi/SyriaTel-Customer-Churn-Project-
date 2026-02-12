# SyriaTel-Customer-Churn-Project

# Overview
A machine learning project that uses the SyriaTel Customer Chun dataset. The Machine Learning model will help predict whether a SyriaTel Telecommunications customer is at risk of churning (stop doing business wit the company).The objective is to assist the company in recognizing customers who are at high risk of churning early, allowing them to implement measures to retain them.

# Business and Data Understanding

### Business Problem
Customer churn is costly for telecom providers because:

- Acquiring new customers is more expensive than retaining existing ones
- Lost customers mean lost recurring revenue

Goal of this project is to help Syriatel is looking for a reliable way to predict customers likely to churn so that the company can take correctve action.

# Data Source
* SyriaTel Customer Churn Dataset- https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset

## Stakeholders 
The primary stakeholders of this project are: 

* Management Team
* Customer Engagement Team

# Data Preparation

Before modeling:

1. Irrelevant columns such as `phone number` and `state` were dropped.
2. Categorical variables (`international plan`, `voice mail plan`) were encoded to numeric.
3. The target column `churn` was correctly converted to integers.
4. Train-Test split was performed with stratification to preserve class distribution.

# Modeling

- Logistic Regression was used
- Decision Tree classifier model was used

### Final Model — Decision Tree Classifier

- Chosen as the final model because it achieved stronger "**recall**" on detecting churn customers and appaears to be more reliable compared to the previous model.

---

# Evaluation

To evaluate model performance, **recall** was selected as the primary metric because:

-It measured how many actual churn customers were correctly identified by the model (our main business objective)
--- The final Decision Tree model was evaluated on holdout test data.---

# Conclusion

> With the Decision Tree model, SyriaTel can now 
-Target high risk customers likely to churn through sending promotions and offers to retain them.
-Deploy better customer service strategies to meet the customer needs on time
- Increase customer retention and hence increase revenue retention


