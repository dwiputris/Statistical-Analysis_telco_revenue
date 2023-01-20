# Statistical_Data_Analysis_telco_revenue
In this project, statistical data analysis approach is employed to decide which hypothesis to be rejected. Scipy Stat library is used to find the pvalue that will determine if Hypothesis Null should or should not be rejected.
A telecommunication operator company is analysing its two lines of service for the revenue they generate. 
The company wishes to know which segments it should focus its marketing resources on based on the revenue they contribute.

Hence the end purposes of this project are:
1. To understand how each telco plan generates different revenue amount
2. To understand how clients in city NY-NJ contributes different revenue amount
3. To understand how clients' behavior of each of two plans are different in using call, internet, and message service.

The start of this analysis is pre-processing, with steps:
1. Checking missing values, duplicates, and mismatch data type
2. Merging all needed tables
3. Adding more columns that are needed in furher feature engineering and analysis, that is: i. month generating revenue ii. extra service used iii. additional charges for extra service iv. total payment including all additional charges

The first data analysis conducted is Exploratory Data Analysis (EDA). It appears that:
1. For all the three services, clients of both Surf and Ultimate increase their use from Jan to Dec during 2018. The proportion of month-on-month increase in each of two plans looks similar.
2. During month 1 to 6 in 2018, total payment of clients Ultimate is bigger than of Surf for a slight amount. But in month 7 to 12, Surf clients pay a lot more than Ultimate. This is contrary to the amount of monthly plan payment where Ultimate clients constantly pay higher for every month in 2018 compared to Surf. This means that although monthly payment plan for Surf is smaller than Ultimate, clients of Surf pay a lot more for extra services they use, especially during July to December.
3. Surf clients enjoy extra use of service all for calls, messages, and internet. While Ultimate clients stick with their monthly allotment, except for internet service, yet still is very small compared to Surf.

The next data analysis is statistical analysis. It is known that:
1. Average revenue generated from clients of Surf is different from of Ultimate
2. Average revenue generated from clients of New York - New Jersey is the same with of other cities
