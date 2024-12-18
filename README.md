# Booking-Stability

Project Overview

This project aims to analyze hotel booking data to identify the key factors that contribute to cancellations and develop strategies to reduce the cancellation rates. By leveraging data analysis techniques using pandas, we can provide actionable insights to improve booking stability.

Introduction

The goal of this project is to reduce the rate of hotel booking cancellations. Cancellations can cause significant revenue loss and affect the operational planning of hotels. By identifying patterns and factors leading to cancellations, hotels can take proactive measures to minimize these occurrences.

Data Collection

Details on the data used in the project:

Source: Mention the source of the data (e.g., Kaggle, internal hotel booking system).

Type of Data: Describe the data (e.g., booking details, customer demographics, booking dates, cancellation status).

Data Preprocessing

Steps taken to clean and prepare the data for analysis:

Handling Missing Values: Techniques used to handle missing data (e.g., filling with mean/median, dropping rows).

Data Normalization: Normalizing numerical features if needed.

Encoding Categorical Variables: Converting categorical variables into numerical values using pandas.

Data Cleaning: Removing duplicates and correcting inconsistent data entries.

Exploratory Data Analysis

Key findings from the initial data analysis:

(i) Calculating the percentage of canceled and non-canceled bookings
![image](https://github.com/user-attachments/assets/6db61546-38cc-4a7a-a1d4-918d0b4a1467)


We calculated the percentage of both canceled and non-canceled bookings based on the provided data. Our analysis reveals that 62.87% of bookings remain non-canceled, while 37.13% have been canceled. This indicates a substantial portion of reservations experiencing cancellation, highlighting the potential impact on hotel operations and revenue. Understanding these percentages allows for a deeper comprehension of booking trends and aids in strategic decision-making for hotel management.

(ii) Reservation status across different hotels

![image](https://github.com/user-attachments/assets/21087b6a-69e2-44ff-8f3f-c2fb15665dfe)


In comparison to city hotels, resort hotels have fewer bookings. It's possible that resort hotels are pricier than those in urban areas.

In resort hotels, most bookings, about 72%, aren't canceled. However, around 27.9% of reservations are getting canceled, which is still quite a sizable portion.

City hotels are facing a high cancellation rate, with 41.7% of reservations getting canceled, while only 58.2% are staying confirmed.

(iii) Average Daily Rate in City and Resort Hotel

![image](https://github.com/user-attachments/assets/e292909c-c7a4-4738-aafb-9b737586c23b)


• The slide shows a visualization comparing the average daily rate (ADR) between city hotels and resort hotels over time.

• The orange line represents the ADR for city hotels, while the blue line represents the ADR for resort hotels.

• We can see that the lines intersect at various points, indicating that the price comparison between the two hotel types fluctuates over time.

• Generally, city hotel prices tend to be lower than resort hotel prices, except during busy periods like holidays and weekends when demand increases and prices rise.

• This supports our hypothesis that city hotel ADR is typically lower than resort hotel ADR, with some exceptions during peak travel times.

(iv) Reservation status per month
![image](https://github.com/user-attachments/assets/fb3440cb-3413-4aad-a34d-ed70c6a3dc17)



• January saw the highest rate of cancellations, while August had the lowest cancellation rate.

• August had the most reservations, while December and January had the fewest.

• These trends in reservation status and cancellations are important to understand seasonal patterns in demand.

• Knowing when peak and low seasons occur can help us optimize staffing, inventory, and other operational decisions.

• Analyzing these monthly fluctuations will allow us to better prepare for and respond to changes in reservation volume.

(v) Average daily rate per month

![image](https://github.com/user-attachments/assets/353c43d9-79d7-4b0b-80e6-344e5d9bc773)


• The data analysis revealed that January had the highest cancellation rate and highest average daily rate, while August had the lowest cancellation rate and lower prices.

• August was the busiest month for bookings, while December and January were slower periods.

• There appears to be a clear relationship between cancellation rates and pricing - higher prices tend to coincide with increased cancellations, while lower prices correspond to decreased cancellation rates.

• This finding highlights the importance of pricing strategies in effectively managing reservation cancellations.

• The insights from this analysis can inform pricing decisions to balance occupancy, revenue, and cancellation rates.

(vi) Top 10 country with reservation canceled

![image](https://github.com/user-attachments/assets/92d280a8-9c4c-4ca4-b7de-4e085b39e7b2)


•Portugal has the highest cancellation rate at 70.07%, significantly higher than the second highest rate of 6.25% in the United Kingdom.

• This stark difference suggests Portugal should consider enhancing its facilities, adjusting pricing strategies, offering more discounts, and running promotional campaigns to reduce the high cancellation rate.

• Improving the customer experience through upgraded amenities and better services can make stays more appealing, thereby reducing cancellations.

• Revisiting pricing models to be more competitive and attractive, coupled with targeted discounts and special offers, can incentivize more bookings and minimize cancellations.

• Effective marketing campaigns can further bolster these efforts by attracting a more committed customer base.

• By addressing these areas, Portugal can work towards aligning its cancellation rates more closely with other countries, stabilizing and potentially increasing its reservation rates.

Suggestions
1.Cancellation rates increase as prices rise. To reduce reservation cancellations, hotels should consider adjusting their pricing strategies and lowering rates for specific locations. Additionally, offering discounts to customers could be beneficial.

2.The ratio of cancellations to non-cancellations is higher for resort hotels compared to city hotels. Therefore, resort hotels should offer reasonable discounts on room prices during weekends or holidays.

3.In January, hotels can initiate marketing campaigns with reasonable budgets to boost revenue, as this month experiences the highest cancellation rates.

4.Enhancing the quality of hotels and services, particularly in Portugal, could help decrease the cancellation rate.
