# Freshco_Hypermart_Excel_Data_Analysis

Freshco Hypermarket, situated in HSR, Bangalore, has established itself as a prominent supermarket in the region, catering to a wide range of customers. In response to evolving customer needs and to enhance convenience, Freshco introduced a home delivery service in the year 2021. To ensure seamless operations and optimize customer satisfaction, the store diligently maintained a comprehensive transaction data sheet, containing detailed information at the order level.

# Dataset 

dataset link: 

1. **Completion rate :** This refers to the rate at which orders are completed (Order successfully delivered / Total order placed).
2. **Customer Lifetime value :** It refers to the total revenue generated per customer. Usually this number is defined across various time period such as 3 month LTV, 6 month LTV or 12 months LTV. However, you don’t need to consider specific time period for this business case. For example, if a person placed 15 orders and paid cumulative 4500 rupees to Freshco, the LTV for the customer is 4500 (excluding discount).

3. **Acquisition month :** First month of transaction by the customer. For example, if you have purchased your first order at Amazon on 15th Jan , 2017, then you as a customer, got acquired by Amazon in Jan 2017. For a user, the acquisition month is always going to be same, it doesn’t change with subsequent transactions. It’s like your birth date, which is always going to be same.

4. **Delivery Area :** It refers to the designated drop-off location where a product or package is intended to be delivered. Refer order geo drop column for this.
5. **Slot definition :** A time slot is a specific interval when a customer chooses to place an order from a specific store or location. Example of time slots: morning, afternoon, evening, night, and late-nightMorning: Orders placed between 5am to 12pm
    
Afternoon: Orders placed between 12pm to 5 pm 

Evening: Orders placed between 5pm to 8pm

Night: Orders placed between 8pm to 11pm

Late Night: Orders placed between 11pm to 5am

7. **Overall delivery time :** It refer as the time difference between the order placed time and the completion time of the delivery process. It measures the total elapsed time required for the entire delivery process (Order time – completed delivery time).

The overall delivery time can be broken down into following-

Order to  Arrival : Order time to Partner Store reach.
Arrival to pickup : Partner Store Reach Time to Partner Start for Delivery Time.
Pickup to Delivery : Partner Start for Delivery Time to Completed/Cancelled Timestamp.

Use both the datasets to solve all of the following questions. You need to create data view for every question and write your brief summary inference on every analysis (Order Level Analysis, Completion Rate Analysis, Customer Level Analysis, Delivery Analysis, Product Level Analysis).
Make sure that you submit/upload both (excel working file and Doc report) files using zip. 

8. **Customer acquisition source :** It is the source from which a customer got acquired to the platform.


# Data Analysis: 

**A. Order Level Analysis:**
1.Identified order distribution at slot and delivery area level.
2.Identified areas with the highest increase in monthly orders (from Jan to Sep) in absolute orders.
3.Calculated delivery charges as a percentage of product amount at slot and month level.
4.Calculated discount as a percentage of product amount at slot and month level.
5.Calculated discount as a percentage of product amount at drop area and slot level.

**B. Completion Rate Analysis:**
1.Identified completion rate at slot vs day of the week (Sunday to Saturday) level and spotted patterns in the data.
2.Calculated completion rate at drop area level.
3.Calculated completion rate at number of products ordered level by creating a column with the number of products per order.
4.Analyzed patterns observed in the completion rate.
5.Customer Level Analysis
6.Identified completion rate at source level.
7.Calculated LTV for every customer.
8.Calculated aggregated LTV at customer acquisition source level.
9.Calculated aggregated LTV at acquisition month level.
10.Determined the average revenue (product amount after discount) per order at different customer acquisition source levels.
11.Determined the average revenue (product amount after discount) per order at acquisition month level.
12.Analyzed patterns in order rating across slots, number of items placed, delivery charges, and discounts.

**C. Delivery Analysis:**
1.Calculated average overall delivery time at month and delivery area level.
2.Calculated average overall delivery time at month and weekday/weekend level by tagging each date as either weekday or weekend.
3.Calculated average overall delivery time at slot level.
4.Identified patterns in delivery charges with slot or delivery area.
5.Identified patterns in delivery time and delivery area and found logical reasons.

# Report:
Please find the reports here
Excel file:
Doc File:
Presentation:
