# Maven_Pizza_Challenge
This is a personal project that uses Power BI to visualize data in the form of charts. Then, I will analyze those charts to get insights to offer some advises for business owner.

## 1. About the dataset
This dataset contains 4 tables in CSV format:
- The Orders table contains the date & time that all table orders were placed
- The Order Details table contains the different pizzas served with each order in the Orders table, and their quantities
- The Pizzas table contains the size and price for each distinct pizza in the Order Details table, as well as its broader pizza type
- The Pizza Types table contains details on the pizza types in the Pizzas table, including their name as it appears on the menu, the category it falls under, and its list of ingredients

## 2. Data Model
![Maven_Pizza_DataModel](https://github.com/dinhminhhuy/Maven_Pizza_Challenge/assets/128075058/a0ba3171-fbe1-463b-b0ca-b7eb111e6206)

## 3. Detailed Analysis
### 3.1 Openning Time
![Openning_Hour](https://github.com/dinhminhhuy/Maven_Pizza_Challenge/assets/128075058/7a9f9d99-cad8-4634-8dfd-dee61f4a3974)

Looking at the table above, we can see that in 2015 the total number of orders that Plato's Pizza received in 2 time periods: from 9 am to 11 am and after 11 pm was 37 orders, accounting for **0.173%** of the total number of orders. Revenue in these two periods is also only **1508 dollars**, this number is equivalent to 0.19% of total sales. Therefore, ***Plato's should be openned at 11 am and closed at 11 pm***. ***Reducing working shifts could save money***. 

Furthermore, don't forget to ***reallocate employees during peak hours*** to satisfy high demand from consumers.

### 3.2 Openning Day
![Quantity_per_day](https://github.com/dinhminhhuy/Maven_Pizza_Challenge/assets/128075058/601caa71-eba0-4d86-986a-a0fecfb6dbe9)

This above table shows that days which have high revenues and quantity of pizzas sold are especially due to holidays.
- St. Patrick's Day (March 17th)
- Independence Day (July 4th)
- Thanksgiving Day (The 4th Thursday in Novenber)
...

=> Plato's needs to forecast in advance the number of customers that may come during the holidays, thereby preparing the right amount of materials and workers to better serve customers.

![Quantity_per_day_of_the_week](https://github.com/dinhminhhuy/Maven_Pizza_Challenge/assets/128075058/fdf0c0bc-e39d-4e97-9adb-e9da25a34565)

This histogram shows that Thursday, Friday and Saturday are 3 days that have the highest quantity of pizzas. So that most employees should be working on these 3 days to satisfy high demand from consumers.

### 3.3 Pizza Categories and Sizes

![pizzas_sold_by_size](https://github.com/dinhminhhuy/Maven_Pizza_Challenge/assets/128075058/3ef99e5a-5e8f-4f29-982e-26b38756901b)

We can see that total revenue by size XL and XXL is extremely low . The marketing team should boost sals by running promotions in the months with lower salesand in the XL and XXL size pizzas. For example, customers who buy pizza from size XL or xxl will get extra points for their membership card, or when buying combos including pizza size XL or xxl will get 1 free drink.
