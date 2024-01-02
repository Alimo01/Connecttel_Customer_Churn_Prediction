# Connecttel_Customer_Churn_Prediction
Predicting customer churn for ConnectTel Telecom. Leverage advanced analytics and machine learning to forecast potential churners, enhancing customer loyalty in the dynamic telecom industry.

## Project Description
ConnectTel, a leading telecommunications company, faces a critical challenge in customer churn, jeopardizing its business sustainability. As A Data Scientist, I developed a precise and effective customer churn prediction system. By leveraging advanced analytics and machine learning on existing customer data, the project aims to accurately forecast churn and implement targeted retention initiatives. This proactive strategy is geared towards reducing customer attrition, enhancing loyalty, and securing ConnectTel's competitive edge in the dynamic telecommunications industry. As you embark on this data-driven journey, the focus is on empowering ConnectTel to fortify customer relationships and thrive in the digital age.

## Steps Taken:
#### Data Cleaning and Exploration:
Conducted comprehensive data cleaning to address issues related to quality and completeness.
Explored the cleaned data to discern patterns and extract meaningful insights. The Data contains the following information.

* CustomerID: A unique identifier assigned to each telecom customer, enabling tracking and identification of individual customers.
* Gender: The gender of the customer, which can be categorized as male, or female. This information helps in analyzing gender based trends in customer churn.
* SeniorCitizen: A binary indicator that identifies whether the customer is a senior citizen or not. This attribute helps in understanding if there are any specific churn patterns among senior customers.
* Partner: Indicates whether the customer has a partner or not. This attribute helps in evaluating the impact of having a partner on churn behavior.
* Dependents: Indicates whether the customer has dependents or not. This attribute helps in assessing the influence of having dependents on customer churn.
* Tenure: The duration for which the customer has been subscribed to the telecom service. It represents the loyalty or longevity of the customer’s relationship with the company and is a significant predictor of churn.
* PhoneService: Indicates whether the customer has a phone service or not. This attribute helps in understanding the impact of phone service on churn.
* MultipleLines: Indicates whether the customer has multiple lines or not. This attribute helps in analyzing the effect of having multiple lines on customer churn.
* InternetService: Indicates the type of internet service subscribed by the customer, such as DSL, fiber optic, or no internet service. It helps in evaluating the relationship between internet service and churn.
* OnlineSecurity: Indicates whether the customer has online security services or not. This attribute helps in analyzing the impact of online security on customer churn.
* OnlineBackup: Indicates whether the customer has online backup services or not. This attribute helps in evaluating the impact of online backup on churn behavior.
* DeviceProtection: Indicates whether the customer has device protection services or not. This attribute helps in understanding the influence of device protection on churn.
* TechSupport: Indicates whether the customer has technical support services or not. This attribute helps in assessing the impact of tech support on churn behavior.
* StreamingTV: Indicates whether the customer has streaming TV services or not. This attribute helps in evaluating the impact of streaming TV on customer churn.
* StreamingMovies: Indicates whether the customer has streaming movie services or not. This attribute helps in understanding the influence of streaming movies on churn behavior.
* Contract: Indicates the type of contract the customer has, such as a month to month, one year, or two year contract. It is a crucial factor in predicting churn as different contract lengths may have varying impacts on customer loyalty.
* PaperlessBilling: Indicates whether the customer has opted for paperless billing or not. This attribute helps in analyzing the effect of paperless billing on customer churn.
* PaymentMethod: Indicates the method of payment used by the customer, such as electronic checks, mailed checks, bank transfers, or credit cards. This attribute helps in evaluating the impact of payment methods on churn.
* MonthlyCharges: The amount charged to the customer on a monthly basis. It helps in understanding the relationship between monthly charges and churn behavior.
* TotalCharges: The total amount charged to the customer over the entire tenure. It represents the cumulative revenue generated from the customer and may have an impact on churn.
* Churn: The target variable indicates whether the customer has churned (canceled the service) or not. It is the main variable to predict in telecom customer churn analysis.


## Feature Engineering:
Augmented the dataset through the encoding of categorical variables and the generation of new features derived from insights obtained during exploratory data analysis (EDA). Modified the data to ensure its appropriateness for training machine learning models.

## Model Development:
Selected and trained at least three supervised learning models, including Gradient Boosting Classifier, Logistic Regression, and Random Forest Classifier.

# Business Recommendations:
The Gradient Boosting Classifier appears to be the best choice for customer churn prediction among the models. Minimizing customer churn is crucial for a firm's profitability. To achieve this, understanding and identifying at-risk customers are key. Prioritizing customer service improvement and building loyalty through personalized experiences are effective strategies. Proactive measures, such as surveying departed customers, help prevent future churn.
