# Customer_Churn_Prediction
This is a project that peaks into real-world business problem. By using voting classifier with estimators of Random Forest, Gradient Boosting Decision Tree, XGBoost and LightGBM, the model reaches accuracy of 77%, which allows fairly accurate prediction of customer churn behavior. More importantly, the feature importance offers insights into how the company can develop strategies to reduce churn rate. Below are some visualizations and scores.


![image](https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/a778bddd-c3e5-4308-b0e3-a5bb931426eb)
* The gender proportions are similar no matter whether the customers churned or not.
* A larger proportion of young citizens chose not to churn compared to the seniors.
* Customers with dependents are less likely to churn.
* Many more customers with month-to-month contract chose to move out compared to those with one-year or two-year contract.
* Customers who opted for credit card transfer or bank transfer and mailed check as payment method were less likely to churn.


![image](https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/f0ea48f8-2bed-4c48-a27b-7d8d04748d01)
* Fewer customers churned as the tenure increased.
* Customers were more likely to churn when the monthly charges were high.
* There was higer churn when the total charges were lower.


![image](https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/b0850d11-ec5b-488d-b6a0-0f23743c19f5)
* Customers without partners generally opted out for the service with smaller tenure values.
* Availability of phone service or not did not affect customers' decision to opt out with respect to tenure period. Customers were probably not heavy phone service users.
* Intuitively, the churn tenure period was shorter for month-to-month contract and longer for two-year contract.
* Customers with streaming TV and movies showed similar churn tenure period of 10-40 months.  


![image](https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/e6b86d50-2cef-4781-ac31-94c6025cc46b)
* Monthly Charges: This feature has very high importance. As shown in the graph above, customers were more likely to churn when the monthly charges were high. Identifying patterns in customer behavior based on different charge levels allows optimizing pricing strategies or targeted promotions to reduce churn rate.
* Tenure: Naturally, fewer customers churn as the tenure increases. Thus, it is important to identify certain tenure thresholds where churn is more likely to occur, so the companies can develop respective strategies to retain customers at these points of time.
* Monthly Charges Ratio: It is a feature related to both monthly charges and tenure. It suggests that companies can examine pricing strategies and identify patterns in customer behaviors.
* Payment Method: Customers who opted for credit card transfer or bank transfer and mailed check as payment method were less likely to churn. Knowing customers' preferences in payment methods allows companies to optimize payment options to reduce churn.
* Contract: Many more customers with month-to-month contract chose to opt out compared to those with one-year or two-year contract. Companies can accordingly encourage longer-term contracts to reduce customer churn.


<img width="471" alt="Screenshot 2023-08-02 at 23 41 17" src="https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/f7c2a7de-55c8-40d9-9376-1344fb489a9d">


![image](https://github.com/Jennyyin20/Customer_Churn_Prediction/assets/52028491/795bddc4-a132-488e-b872-b8beda3b63db)

