### Project Overview: Universal Bank Personal Loan Campaign

#### Objective
The goal of this project is to optimize Universal Bank's outreach for their personal loan offering by predicting which customers will utilize the loan. There's a significant cost associated with contacting all potential customers: a $1.00 mailing fee per customer and an additional $140.00 processing and setup fee for each accepted loan. If a loan is accepted but not utilized, it results in a $141.00 loss for the bank. Conversely, an active loan generates a net profit of $859. To mitigate the risk and maximize profitability, we aim to forecast which customers are most likely to accept and use the loan, based on historical data.

#### Data Analysis and Preparation
To begin, I examined all customer-related columns and their respective data. Data visualizations were created to understand the distribution of personal loan usage across different variables. The data cleaning process involved addressing missing values, correcting data types, and ensuring data integrity by evaluating statistical measures such as mean, minimum, and maximum values. Notably, the 'experience' column contained negative values, which were set to zero for accuracy.

#### Methodology
Several key functions were developed for the analysis:
- **Accuracy Function**: To determine model accuracy.
- **Confusion Matrix**: To evaluate model performance.
- **Gains and Lift Chart**: To assess model improvement over random selection.
- **Profit Calculations**: To provide detailed datasets of predicted outcomes, including total loss, gain, and revenue for each model.

The dataset was split into training and test sets to validate the models' performance. The models employed in this analysis include:
- Full Dataset - was conducted solely to compare the performance of other models when compared to the entire dataset
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Ensemble Methods
- Random Forest

Performance metrics such as accuracy, net profit, loan acceptance rate, number of customers to contact, cost, and revenue were compiled into a new dataset for comprehensive model comparison.

#### Results and Recommendation
The Random Forest model emerged as the top performer, exhibiting the highest net profit and accuracy score. Therefore, this model is recommended for predicting which customers to target for the personal loan offering.

By implementing the Random Forest model, Universal Bank can strategically contact potential loan customers, thereby minimizing costs and maximizing profitability.
