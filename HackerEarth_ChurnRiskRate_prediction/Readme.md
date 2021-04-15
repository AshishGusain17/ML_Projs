## Problem overview
Churn rate is a marketing metric that describes the number of customers who leave a business over 
a specific time period. Every user is assigned a prediction value that estimates their state of 
churn at any given time. This value is based on:

* User demographic information
* Browsing behavior
* Historical purchase data among other information

It factors in our unique and proprietary predictions of how long a user will remain a customer. 
This score is updated every day for all users who have a minimum of one conversion. 
The values assigned are between 1 and 5.


## Task
Your task is to predict the churn score for a website based on the features provided in the dataset.


## Data Description :

* **customer_id**	Represents the unique identification number of a customer
* **Name**	Represents the name of a customer
* **age**	Represents the age of a customer
* **security_no**	Represents a unique security number that is used to identify a person
* **region_category**	Represents the region that a customer belongs to 
* **membership_category**	Represents the category of the membership that a customer is using
* **joining_date**	Represents the date when a customer became a member 
* **joined_through_referral**	Represents whether a customer joined using any referral code or ID
* **referral_id**	Represents a referral ID
* **preferred_offer_types**	Represents the type of offer that a customer prefers
* **medium_of_operation**	Represents the medium of operation that a customer uses for transactions
* **internet_option**	Represents the type of internet service a customer uses
* **last_visit_time**	Represents the last time a customer visited the website
* **days_since_last_login**	Represents the no. of days since a customer last logged into the website
* **avg_time_spent**	Represents the average time spent by a customer on the website
* **avg_transaction_value**	Represents the average transaction value of a customer
* **avg_frequency_login_days**	Represents the no. of times a customer has logged in to the website
* **points_in_wallet**	Represents the points awarded to a customer on each transaction 
* **used_special_discount**	Represents whether a customer uses special discounts offered
* **offer_application_preference**	Represents whether a customer prefers offers 
* **past_complaint**	Represents whether a customer has raised any complaints 
* **complaint_status**	Represents whether the complaints raised by a customer was resolved 
* **feedback**	Represents the feedback provided by a customer
* **churn_risk_score**	Represents the churn risk score that ranges from 1 to 5




## Evaluation Metric

score = 100 x metrics.f1_score(actual, predicted, average="macro")
