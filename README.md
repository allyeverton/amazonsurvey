# amazon_consumer_survey

## Project description
[link to public tableau visialization](https://public.tableau.com/app/profile/allison.everton/viz/AmazonConsumerHabitsSurvey/Sheet1#1) 

This document is a repository for the class project of MGT 4250 Fall 2023 at Elon University. This projects analyzes an data set from an Amazon customer survey.   

### Questions of interest
The interets of this analysis is the purchasing and browsing tendency of shoppers on Amazon. 
- How can we analyze consumer behavior to increase consumer purchases?
- What is the main cause of a consumer to not make a purchase?

These questions are important for developing marketing campaigns that target a specific group with the goal of increasing revenues. Amazon can identify new growth opportunities and create targeted ad campaigns. A [reference](https://www.linkedin.com/pulse/beyond-borders-why-consumer-behaviour-market-trends-important/) is included on why this project has important implication and why Amazon and all businesses should be analyzing consumer behavior.

## Data Description
This data was found from Kaggle and converted from a csv file to an excel file to be used in Tableau. Access the Kaggle site [here](https://www.kaggle.com/datasets/swathiunnikrishnan/amazon-consumer-behaviour-dataset). 

A majority of the questions are answered with drop-down selections with limited options (no free response) 

Out of the 24 variables in this dataset, this analysis uilizes the following:
1. Age (int): age of surveyor
2. Gender (str): Gender (Female, Male, Other)
3. Purchase_Frequency (str): How frequently do you make purchases on Amazon?
4. Purchase_Categories (str): What product categories do you typically purchase on Amazon?
5. Browsing_Frequency (str): How often do you browse Amazon's website or app?
6.Cart_Abandonment_Factors (str): What factors influence your decision to abandon a purchase in your cart?
7.Improvement_Areas (str): Are there any areas where you think Amazon can improve?
## Interpreting Visualizations

### Bar Chart
![image](https://github.com/allyeverton/amazonsurvey/assets/152214878/4fa7ae18-9c98-457a-be08-cd71c00cc2b2)
The bar chart shows the average age of each combination of browsing and purchase frequency. Similar to the previous visualization, we can use this to identify what age group to target when looking to close the browsing and purchasing gap. The biggest thing that jumps out is that there is no clear pattern between age group and the browsing and purchasing frequency. The group that we do want to focus on is people who browse multiple times a day but purchase very infrequently (less than once a month). The average age for that group is around 26. We can use this information to provide targeted advertisements to young adults or send out more surveys to just that age group to understand why they are not purchasing more.

### Stacked Bar Chart
![image](https://github.com/allyeverton/amazonsurvey/assets/152214878/7e072f8c-16b3-4f9a-80aa-ff79b3443201)
The stacked bar chart shows the breakdown of each gender's browsing and purchasing frequency. This graphic can help us identify what gender to target certain ads or promotions to close the gap between their purchasing and browsing history. From the chart, we can see that a large amount of the surveyors browse a few times a week. The large majority of those customers only make purchases a few times a month and most of those customers are women. We can see that Women are most likley to browse weekly but only purchase monthly. Amazon must target women who browse weekly and incentivise them to purchase more. This could look like email corespondence about sales on items they were browsing.

### Heat Map
![image](https://github.com/allyeverton/amazonsurvey/assets/152214878/be9caaa4-d520-4821-b420-62cdc6505bbf)
The heat map shows the largest categories of reasons for cart abandonment and areas of improvement. This can help us identify ways to increase purchase frequency. The largest areas for improvement are customer service responsiveness. To increase a customers purchase frequency, the results suggest that Amazon should invest in increasing customer service responsiveness. This could look like hiring more customer service representatives or improving their current system. The largest factor leading towards a customer abandoning their cart is that they found a better price elsewhere. To convert that abandoned cart into a purchase, Amazon must stay competetive on price. This could look like targeted promotions, sales, price matching, or providing something extra that warrents the higher price. 

## Discussion & Summary

### Article
In an [article](https://hospitalityinsights.ehl.edu/understanding-consumer-behavior#:~:text=Understanding%20consumer%20behavior%20is%20a%20valuable%20tool%20for%20product%20and,services%20that%20meet%20those%20needs.) by Ana McFee from EHL, there is a discussion surrounding consumer behavior and how that can lead and influence business decisions. She asks the question "Why is Consumer Behavior so important?". To answer that question she provides a list of improvements to a business:
- improve marketing and communication
- improve customer retention rates
- increase customer loyalty
- better predit trends in consumer behavior
- increase ability to stay relevant
- increase sales
- innovate attractive new services and products

The article then describes factors that affect consumer decision making, types of consumer behavior, and ways for businesses to collect data on consumer bahavior.

### ChatGPT
[Full Questions and Answer Link](https://chat.openai.com/share/2bd2edb2-38bd-4aed-b210-2d85b1d06667)

#### How can we analyze consumer behavior to increase consumer purchases?
Customer Survey and Feedback was identified as a method which aligns with our analysis and the artices suggestions on data collection. 

Limited-Time Offers was also identified as a method to ecourage increase in consumer action. In our bar charts visualizations we identified a consumer segment that this method could be implemented on to increase their purchase frequency to meet their browsing frequency.

#### What is the main cause of a consumer to not make a purchase?

Common factors that contribute to a customer not making a purchase (in our analysis we looked at cart abandonment factors and areas of improvement) 
