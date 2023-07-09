# Hotel-Booking-Analysis
**Index**
1. Project Summary
2. Problem Statement
3. Know Your Data
4. Understanding Your Variables
5. Data Wrangling
6. Data Vizualization, Storytelling & Experimenting with charts : Understand the relationships between variables
7. Solution to Business Objective
8. Conclusion

# **Project Summary** -
* The Hotel Booking Analysis project is an in-depth exploratory data analysis (EDA) project focused on analyzing hotel booking data to extract valuable insights and make data-driven observations. The project addresses various aspects of hotel bookings, including cancellations, booking ratios between resort and city hotels, percentage of bookings per year, monthly customer counts, guest origins, average monthly rates per person, weekday versus weekend bookings, hotel availability, total bookings and revenue across years, preferred hotels and stay durations, and length of stay.

* The project begins by cleaning and preprocessing the dataset to ensure data quality. Through data exploration and visualization, we determine the number of bookings that were cancelled and examine the factors contributing to cancellations. Next, we calculate the booking ratio between resort hotels and city hotels to understand customer preferences and identify any significant differences in booking patterns. We also analyze the percentage of bookings for each year to identify booking trends and seasonality.

* Furthermore, we investigate the monthly customer counts received by each hotel to identify peak periods and seasonal variations in customer traffic. By determining the country from which most guests come, we gain insights into customer demographics and tailor marketing strategies accordingly. The average monthly rate per person is calculated to understand pricing trends and assess the competitiveness of hotels in the market.

* Additionally, we analyze the number of bookings made on weekdays versus weekends to identify any significant differences in customer behavior and booking patterns. We also assess hotel availability for booking and provide insights to hotel managers to optimize inventory management and improve booking efficiency.

* Moreover, the project explores the total number of bookings across different years, analyzing booking growth and trends. We split the total revenue across years by hotel type to evaluate revenue trends and compare the performance of different hotel types.

* Lastly, we investigate the preferred hotels where guests like to stay and spend more time. By differentiating between weeknight and weekend stays, we gain insights into customer preferences and behavior. Additionally, we analyze the length of stay in hotels to understand typical stay durations and any correlations with factors such as hotel type or booking month.

Through comprehensive data analysis, visualization, and interpretation, this project provides valuable insights into hotel booking patterns, customer behavior, revenue trends, and guest preferences. The findings can guide strategic decision-making, marketing efforts, and overall business optimization for hotel establishments.
# Problem Statement
**Hotel industry is a very volatile industry and the bookings depend on variety of factors such as type of hotels, seasonality, days of week and many more. This makes analyzing the patterns available in the past data more important to help the hotels plan better. Using the historical data, hotels can perform various campaigns to boost the business. We can use the patterns to predict the future bookings using time series or decision trees.**

We will be using the data available to analyze the factors affecting the hotel bookings. These factors can be used for reporting the trends and predict the future bookings.

**We will be tackling this problem statement**:

1. How Many Booking Were Cancelled?
2. What is the booking ratio between Resort Hotel and City Hotel?
3. What is the percentage of booking for each year?
4. What is the monthly customers each hotel is receiving?
5. From which country most guests come?
6. What is the average monthly rate per person?
7. Number of bookings on weekday vs weekends.
8. Hotels available for booking.
9. Total bookings across years.
10. Total revenue across years split by hotel type.
11. Check in which hotel people like to stay and spend more time.
(a). We will check for the week nights stay.
(b). We will check for the weekends stay.
12. How Long People Stay in the hotel?

* **Define Your Business Objective?**
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyse the data to discover important factors that govern the bookings.
# Know Your Data
* Import Libraries
* Dataset Loading
* Dataset First View
* Dataset Rows & Columns count
* Dataset Information
* Duplicate Values
* Missing Values/Null Values
![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/630d2b40-3c36-4900-8e7b-98baadf6fbde)
![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/6776666b-5e68-4926-a579-6578176bd7b1)
* Finding Outliers in the DataSet
![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/ef3a3481-1db4-44a2-8869-a276e34e07b0)


* What did you know about your dataset?

# Understanding Your Variables
* Check Unique Values for each variable.

# Data Wrangling
* Data Wrangling Code
* What all manipulations have you done and insights you found?

#  Data Vizualization, Storytelling & Experimenting with charts : Understand the relationships between variables
* **Chart - 1: How Many Booking Were Cancelled?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/94aee74b-7881-434f-9fe8-72605e39ac42)


* **Chart - 2: 2. What is the booking ratio between Resort Hotel and City Hotel?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/affd9bb2-3d91-46f8-b3a3-5e6a1f5746bd)



* **Chart - 3: What is the percentage of booking for each year?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/4f616a37-3990-45a6-b118-d9328c6354ff)


* **Chart - 4: What is the monthly customers each hotel is receiving?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/3aa81969-6b04-4a54-abeb-398057d696ed)


* **Chart - 5: From which country most guests come?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/010713e6-b771-4f24-b3a1-09c6fcd70117)


* **Chart - 6: What is the average monthly rate per person?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/a2d0b01c-69a9-43af-9996-701f8905f118)


* **Chart - 7: Number of bookings on weekday vs weekends.**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/e55b5446-da24-4033-ba85-d2f64473a42b)


* **Chart - 8: Hotels available for booking.**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/8896c2c2-76c0-46ef-a436-73bb8bdd4bd4)


* **Chart - 9: Total bookings across years.**
* Total bookings across years:

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/420c8768-4325-46f7-a3e3-93c3d0a1f736)

* Total bookings across years by hotels:

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/9e3225f2-ed65-43c4-93fb-8cf090c5f9ec)


* **Chart - 10: Total revenue across years split by hotel type.**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/a4c2752d-f6fd-4d24-a101-45eccc3447e8)


* **Chart - 11: Check in which hotel people like to stay and spend more time.**

(a). We will check for the week nights stay.

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/0e4a9c08-3826-422e-bdab-0fdf1ff2d04a)

(b). We will check for the weekends stay.

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/df021b9b-3ee5-4435-9365-1834a4ac4935)


* **Chart - 12: How Long People Stay in the hotel?**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/289de4be-da03-40df-bccb-bb88a8b426b2)


* **Chart - 13: Correlation Heatmap**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/9562aabe-344c-4614-a6cd-8a52579c1425)


* **Chart - 14: Pair Plot**

![image](https://github.com/humayel1/Hotel-Booking-Analysis/assets/134964717/1e6d12fa-1022-4961-97de-c697d7ec951e)


# Solution to Business Objective
**What do you suggest the client to achieve Business Objective ?
Explain Briefly.**

Based on the Hotel Booking EDA conducted, I would suggest the following recommendations to help the client achieve their business objectives:

* **Improve Booking Cancellation Rate**: Analyze the factors contributing to booking cancellations and implement strategies to reduce cancellations. This could include optimizing the booking process, offering flexible cancellation policies, and enhancing communication with guests to understand their needs better.

* **Focus on Marketing and Promotion**: Identify the countries from which most guests come and tailor marketing efforts to target those specific markets. This could involve collaborating with local travel agencies, leveraging social media platforms, and offering promotions or packages that cater to the preferences of guests from those countries.

* **Optimize Revenue Generation**: Continuously monitor and analyze revenue trends across years to identify periods of growth or decline. Based on these insights, implement revenue optimization strategies such as adjusting pricing strategies, optimizing room availability and rates, and offering personalized services or packages to increase revenue.

* **Enhance Guest Experience**: Use the insights gained from the analysis of the length of stay to improve the overall guest experience. This could involve providing personalized services, implementing loyalty programs, offering additional amenities or activities to extend guest stays, and ensuring efficient check-in and check-out processes.

* **Improve Operational Efficiency**: Analyze the distribution of bookings on weekdays and weekends to optimize staffing levels, resource allocation, and service availability. This will help ensure that the hotel is adequately staffed during peak periods and can efficiently manage guest needs and preferences.

* **Monitor Competitor Performance**: Keep track of the performance and offerings of competitors in the hotel industry. This will provide valuable insights into market trends, customer preferences, and potential areas for improvement or differentiation.

* **Collect and Utilize Guest Feedback**: Implement a systematic process to collect guest feedback and reviews to understand their experiences and identify areas for improvement. Utilize this feedback to enhance service quality, address customer concerns, and exceed guest expectations.

By implementing these recommendations, the client can aim to achieve objectives such as reducing booking cancellations, increasing revenue, improving guest satisfaction, and staying competitive in the hotel industry. Regular monitoring, analysis, and adaptation of strategies based on data insights will be essential to drive positive business outcomes.

# **Conclusion**
In conclusion, the Hotel Booking EDA conducted on the dataset has provided valuable insights into various aspects of hotel bookings, guest behavior, and revenue generation. The analysis has shed light on important trends, patterns, and factors that can impact the success of the hotel business.

# The key findings from the EDA include:
* **Booking Cancellations**: A significant number of bookings were found to be canceled. This highlights the importance of understanding the reasons behind cancellations and implementing strategies to reduce them.

* **Booking Ratio**: The booking ratio between the Resort Hotel and City Hotel was examined, indicating the preferences of guests for each type of hotel. This information can be used to tailor marketing efforts and allocate resources accordingly.

* **Weekday vs. Weekend Bookings**: The analysis of bookings on weekdays versus weekends revealed insights into the demand patterns during different days of the week. This knowledge can guide operational decisions and resource allocation.

* **Revenue Generation**: The total revenue across years and split by hotel type was analyzed, providing an overview of the revenue trends. This information can help in identifying periods of growth and implementing revenue optimization strategies.

* **Guest Origin**: The country from which most guests come was identified, providing an opportunity to target marketing efforts and tailor services to cater to the needs and preferences of guests from that specific country.

* **Length of Stay**: The analysis of how long people stay in hotels provided insights into guest behavior and can be used to enhance the guest experience, optimize room availability, and improve operational efficiency.

# Based on these findings, several recommendations can be made to achieve the business objectives:
* Focus on reducing booking cancellations through improved communication and flexible policies.

* Target marketing efforts towards countries with a high number of guests.

* Implement revenue optimization strategies based on revenue trends and performance analysis.

* Enhance guest experience through personalized services, loyalty programs, and efficient check-in/check-out processes.

* Optimize operational efficiency based on booking patterns and demand trends.

* Monitor competitor performance and adapt strategies accordingly.

* Collect and utilize guest feedback to continuously improve services.

By implementing these recommendations, the hotel can improve its overall performance, increase revenue, enhance guest satisfaction, and stay competitive in the market.

It is important to note that the success of these recommendations depends on regular monitoring, analysis of data, and adaptation of strategies based on changing market dynamics and guest preferences. By embracing data-driven decision-making and continuous improvement, the hotel can position itself for long-term success in the highly competitive hospitality industry.


