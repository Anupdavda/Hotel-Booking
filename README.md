# Hotel-Booking
Recently there has been a spike in high cancellation rates, resulting in a loss in revenue. The goal of this project is to analyze the data to reduce hotel reservation cancellations and increase revenue.

# Overview
* This project focuses on Exploratory data analysis (EDA).
* Engineered features to convert Categorical values to Numerical Values.
* Removed Outliers and Null values to analyze the data.

# Research Questions
1. What variables affect reservation cancellations?
2. How to effectively reduce the cancellation rate?
   
# Hypothesis
1. Hotel reservation cancellation is directly proportional to the price. As the price increases, reservation cancellation increases.
2. Most reservation cancellation comes from third-party booking.

# EDA

![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/1.png "Histogram of features")
* A greater number of reservations remain unaffected in comparison to the ones that have been canceled. The cancellation rate stands at 37%, a noteworthy factor impacting revenue. Further investigation is necessary to determine the underlying reasons behind these cancellations.
  
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/2.png "Histogram of features")
* City hotels receive a higher number of reservations in comparison to resort hotels, suggesting that the latter may be relatively more expensive than the former.
  
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/3.png "Box Plot Showing Outliers")
* The line graphs above illustrate that on certain days, the average daily rate for city hotels is lower than that of resort hotels, and on other days, it is even lower. It is evident that weekends and holidays generally result in higher rates for resort hotels.
* The Line graph suggests a correlation between reservation cancellations and hotel prices. It shows that cancellations are more common when prices are at their highest and least common when prices are at their lowest. However, it is important to note that correlation does not necessarily imply causation.

* While the graph indicates a relationship between prices and cancellations, it does not conclusively prove that hotel prices are the sole factor responsible for reservation cancellations. Other factors, such as travel plans changing, personal circumstances, or even the availability of alternatives, may also play a role in reservation cancellations.

* To establish a more definitive conclusion and identify the primary drivers behind reservation cancellations, further analysis and investigation are needed, taking into account additional variables and potential influencing factors.
  
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/4.png "Correlation")
* Based on the grouped bar graph analysis, it is evident that the month of August has the highest number of reservations, while the month of January experiences the highest number of cancellations. Conversely, the month of August records the lowest number of canceled reservations.
  
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/5.png "Histogram of features")
* Based on the bar graph, it is evident that August has both the lowest hotel room rates and the lowest cancellation rates. This suggests a strong correlation between prices and reservation cancellations.
  
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/7.png "Box Plot Showing Outliers")
![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/8.png "Correlation")
* The bar graph suggests a correlation between reservation cancellations and hotel prices. It shows that cancellations are more common when prices are at their highest and least common when prices are at their lowest. However, it is important to note that correlation does not necessarily imply causation.

* While the graph indicates a relationship between prices and cancellations, it does not conclusively prove that hotel prices are the sole factor responsible for reservation cancellations. Other factors, such as travel plans changing, personal circumstances, or even the availability of alternatives, may also play a role in reservation cancellations.

* To establish a more definitive conclusion and identify the primary drivers behind reservation cancellations, further analysis and investigation are needed, taking into account additional variables and potential influencing factors.

![alt text](https://github.com/Anupdavda/Hotel-Booking/blob/470ac63db146b4436331e8f15333e126e60c3818/graphs/6.png "Histogram of features")



# Suggestions
1. According to the analysis, reservation cancellation increases as the price increases thus proving the hypothesis. Introducing point base system to offer a discount to loyal customers. Partnering with credit card companies to offer special prices for their customers.
2. Based on the chart, Resort hotels have higher cancellation rates compared to city hotels. Creating personalized holiday packages for families and tourists will help to increase the reservation.
3. Month of January has the highest cancellation rate. Hotels can offer discounted rates for customers.
4. Portugal has the highest cancellation rate. Increasing the services and hospitality may increase the reservation rate.
