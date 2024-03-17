# Retail-Analytics-PowerBI
![image](https://github.com/RavindraSingh90/Retail-Analytics-PowerBI/assets/149532478/902fb75f-a858-4464-b57e-071d86b68c77)

### About Data:

The below data sets were provided by our client (one of leading eCommerce company). This data is about customer behavior which contains data of multiple user events. The duration of the data for two months.
  1. Sales_Data_Ecommerce : The entire customer behavior data 
  2. Promotion: This is promotion data set of special promotions for that day. One product will be promoted in first page of app/website. In addition to that there are many promotions running however the data is limited special promotion.

### Business Questions:
The below are few Sample business questions to be addressed as part of this analysis. However, this is not exhaustive list, and you can add as many as analysis to the dashboards.
1. How is price varying by brand/category/time/channel?
2. Is traffic varied by day/time/channel?
3. Define & calculate high level metrics like (Revenue, potential revenue, products, categories etc…) by month, time, state, channel etc…
4. What is Activity by Brand or category, brad preference, Brand activity by various parameters etc...?
5. How is the search behavior like Brand Search by Category/Category search by Brand?
6. What is effect of Special Promotions?
7. How Pricing fluctuations effecting sales?
Etc…

### Data Dictionary:
#### “Sales_Data_Ecommerce “ Data Set:
user_id: Unique id of customer
event_date: Date of event
Day_of_Week: Day of week of the event
Channel: Which channel used (App/Browser)
event_time: Time of event
event_hour: Hour of event
event_timezone: Time zone
event_type: Type of event (view, cart, purchased)
product_id: Unique id of product
category_id: Unique id of category
category: Category description
sub_category1: Sub category description-level1
sub_category2: Sub category description-level2
brand: Brand name
price: Price of product
user_session: Unique id of user session
State: State
User_Score: Segmentation of customer

#### “Promotions“ Data Set:
Promotion Id: Promotion Type
Date: Date of promotion
Discount: Discount%
ProductId: Unique id of product
