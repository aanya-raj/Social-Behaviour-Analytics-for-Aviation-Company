# Social-Behaviour-Analytics-for-Aviation-Company

## Introduction
An aviation company that provides domestic as well as international trips to the customers now wants to apply a targeted approach instead of reaching out to each of the customers. This time they want to do it digitally instead of tele calling. Hence they have collaborated with a social networking platform, so they can learn the digital and social behavior of the customers and provide the digital advertisement on the user page of the targeted customers who have a high propensity to take up the product.

## Objectives
To harness the available data of existing and potential customers and improve marketing expenditure, thus avoiding high costs
To predict social behavior of the customers and provide the digital advertisement on the user page of the targeted customers who have a high propensity to take up the product

### Key Questions
* What key variables are important in identifying potential purchasing customers?
* What are the different characteristics of the Customers who bought the packages?
* What's the important performance metric for the model and how can it be improved?

### Data
The data used in this project includes information on customer demographics, device preference, social behavior, and travel preferences. The dataset contains the following attributes:

* UserID: Unique ID of user
* Taken_product: Buy ticket in next month
* Yearly_avg_view_on_travel_page: Average yearly views on any travel-related page by user
* preferred_device: Through which device user preferred to do login
* total_likes_on_outstation_checkin_given: Total number of likes given by a user on out of station checkings in last year
* yearly_avg_Outstation_checkins: Average number of out of station check-in done by user
* member_in_family: Total number of relationship mentioned by user in the account
* preferred_location_type: Preferred type of the location for traveling of user
* Yearly_avg_comment_on_travel_page: Average yearly comments on any travel-related page by user
* total_likes_on_outofstation_checkin_received: Total number of likes received by a user on out of station checkings in last year
* week_since_last_outstation_checkin: Number of weeks since last out of station check-in update by user
* following_company_page: Weather the customer is following company page (Yes or No)
* montly_avg_comment_on_company_page: Average monthly comments on company page by user
* working_flag: Weather the customer is working or not
* travelling_network_rating: Does user have close friends who also like traveling. 1 is highs and 4 is lowest
* Adult_flag: Weather the customer is adult or not
* Daily_Avg_mins_spend_on_traveling_page: Average time spend on the company page by user on daily basis


## Data Analysis and Results
* Based on the analysis of the data, it was found that only a small percentage of customers actually end up purchasing a package (16.1%). This suggests that there is a significant imbalance in the dataset and that the company may need to focus on finding ways to increase customer engagement and conversion.

* The majority of customers prefer to use mobile devices for browsing and making purchases (90.6%). This highlights the importance of ensuring that the company's digital platforms are optimized for mobile use.

* The data also shows that the majority of customers have a family size of 3 members (38.9%). This could be used to target marketing efforts towards families, and possibly offer family-specific packages and discounts.

* 84.6% of the customers are not working which can be used to target the advertisement to people who have free time to travel.

* The data also indicates that customers have a preference for beach locations and taking the product for financial or
business reasons. This can be used to create targeted marketing campaigns and product offerings that align with these preferences.

* Only 27.9% of customers follow the company page, this suggests that the company should focus on increasing their online presence and engagement.

* For modeling, various algorithms were used and the best performance was obtained by Random Forest algorithm with accuracy of 89.8% and F1-Score of 0.58868 for mobile data.

## Conclusion
The analysis of the data provides valuable insights into the behavior and preferences of the company's customers, which can be used to improve marketing strategies and increase conversion rates. The results of the modeling also suggest that the Random Forest algorithm is the best choice for predicting customer behavior in this dataset.

This project is a good example of how data analysis and machine learning can be used to improve the business outcomes. By using the insights gained from this analysis, the company can target their marketing efforts more effectively and increase their revenue.

## Note
The data used in this project is fictional and the result obtained is also not accurate, it's just an indicative analysis.


## References
https://www.kaggle.com/
https://scikit-learn.org/stable/
## Contact
For any queries or suggestions, please contact me at [aanya.rajsingh@yahoo.in].



