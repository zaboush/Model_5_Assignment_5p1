# Will the Customer Accept the Coupon?
**Assignment Jupyter Notebook URL Address:** https://github.com/zaboush/Model_5_Assignment_5p1/blob/main/prompt.ipynb
## Project Objectives
The goal of this project is to use what we have learnt over the past few weeks about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 
There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).
## Data Description
The provided data came from the UCI Machine Learning Repository which was originally collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. 
There are three possible answers people can choose from:
“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0”.
## Problem Statement
To provide a brief report that highlights the differences between customers who did and did not accept the coupons. Todo that, we need to explore the data provided using our knowledge of plotting, statistical summaries, and visualization using Python. Then publish our findings in a public facing github repository alongside Pthon code used to analyse the data and conclusions drawn.
## Analyzed Data Findings
**Two coupons were explored and analyzed:**  
1- Bar coupons: The data analyses conducted suggest that people who visits bars more than once a week have significant coupon acceptance rate; Within this group, people who visits bars more than 3 times a week have much higher acceptance rate than people who visits bars 3 times a week or less. Data also suggests that people who visits cheap restaurants 4 or more times a week are the people who mostly accepted the bar coupons. The above conclusion seems intuitive and make sense, people who likes to drink and eat outside quite often would welcome these coupons.  
2- Coffee Houses Coupons: The data analyses conducted showed that the more the frequency of visiting coffee houses the larger the acceptance rate, and people with frequency of 1~3 and above seems to have steady acceptance rage of 64% on average. The data also suggests the maximum acceptance occurs on sunny days at 10AM and for people under the age of 21 years old. Lastly, people heading home have the least acceptance rate while people going to work or none urgent destinations seem to have the highest rate,
## Recomendation
I would recomend adding the geographic location of the car when the coupon presented, since different locations throughout the day may suggest different group of people. For example, a person driving to his/her home is unlikely to stop for a coffee. Whie a driver that just finished his/her workout in a gym may well feel hungry and thirsty and immediately accept the coupons for refreshments.
