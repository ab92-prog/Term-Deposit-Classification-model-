# Term-Deposit-Classification-model-
## Inference and Model Performance Presentation

### Age Distribution:
- The majority of customers fall within the age range of 20 to 60 years, indicating a broad customer base.
- Age can be a relevant factor in determining subscription likelihood.

### Relationship between Job and Balance:
- Retired customers have the highest balance, followed by customers in management and self-employed positions.

### Relationship between Age and Balance:
- Surprisingly, the highest balance is observed at the age of 84, while other ages mostly have similar balances.

### Relationship between Marital Status and Balance:
- The highest average balance is observed among married individuals, followed by single and divorced individuals.

### Boxenplots Analysis:
Both boxenplots show the distribution of age across different categories ('housing' and 'loan') and the impact of the target variable ('y') on that distribution. The plots provide insights into how the age is distributed within each category and whether there are any differences in age distribution based on the housing loan or personal loan status.

### Inference:
Based on the data and visualizations, several inferences can be drawn regarding the marketing campaign and client subscriptions for term deposits. These inferences provide valuable insights into customer behavior and can inform decision-making. Here are the key inferences drawn from the data:

1. **Age Influence:** Targeting marketing efforts towards the age group of 20 to 60 years could yield positive subscription results.

2. **Balance and Subscription:** Customers with balances between 0 and 20,000 euros are more likely to subscribe.

3. **Call Duration Impact:** Longer call durations indicate more engagement and interest from customers.

4. **Contact Days:** Contacting customers within a shorter time frame after their last interaction may be more effective in influencing their decision to subscribe.

5. **Occupation and Balance:** Retired customers have the highest average balance. Tailored marketing messages for this segment could lead to better subscription results.

6. **Marital Status and Loans:** Married individuals have the highest number of personal loans. Campaigns can target married individuals for term deposit subscriptions.

7. **Education and Balance:** Customers with tertiary education tend to have the highest average balance. Consider education levels when identifying target segments.

8. **Seasonal Behavior:** November, October, and December have the highest average balances, indicating saving behavior during festival months.

9. **Housing Loan:** Blue-collar and management job categories show demand for housing loans. They may be receptive to marketing efforts for housing loans and term deposits.

### Modeling Approach:
The predictive modeling approach used in this marketing campaign data is logistic regression classification. Logistic regression is effective for predicting binary outcomes, such as whether a client will subscribe to a term deposit.

1. **Data Transformation:** Categorical columns were one-hot encoded, continuous columns were scaled.

2. **Handling Missing Values:** Missing values were filled with mode (categorical) and mean (continuous).

3. **Model Training and Evaluation:** Logistic regression, decision tree, and random forest models were trained and evaluated.

### Model Performance:
- Logistic Regression: 89.00% accuracy
- Decision Tree Classifier: 82.48% accuracy
- Random Forest Classifier: 88.54% accuracy

The logistic regression model performs the best, making it the preferred choice. It can be used to make predictions on new data and optimize marketing campaigns.

### Final Model and Conclusion:
The final model used for predicting term deposit subscriptions is the logistic regression classification model. It shows the highest accuracy. The model can be utilized to make predictions and provide insights into subscription likelihood, helping the bank optimize marketing strategies for increased subscriptions.

---

Feel free to include this presentation in your documentation to provide a clear overview of the inferences drawn from the data and the performance of the predictive models in the marketing campaign analysis.
