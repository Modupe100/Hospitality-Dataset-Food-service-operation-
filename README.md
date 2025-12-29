# Hospitality-Dataset-Food-service-operation-
# This dataset contains price list and operational data from food service establishments. It is suitable for analyzing revenue trends, menu performance, customer preferences, and service quality.
# Business Questions
What trends exist in customer preferences across menu categories?
How does pricing impact revenue and overall sales performance?
Can sales and demand be accurately predicted using historical data?
How does service quality affect customer satisfaction and operational performance?
# Answer
Customer Preference Trends by Menu Category

Salads (0.1048) show the highest average customer engagement, indicating a strong preference—possibly driven by health-conscious choices or lighter meal options.

Curry (0.0932) ranks second, suggesting steady demand for flavorful, hearty meals.

Sushi (0.0726), Burgers (0.0712), and BBQ (0.0701) fall in the mid-range, showing consistent but moderate customer preference.

Pasta (0.0651) and Pizza (0.0623) have the lowest averages, indicating relatively lower preference compared to other categories.

The overall average (0.0772) suggests customer preference is moderately spread, with clear leaders (Salads and Curry).
# 2.answer 
Pricing Impact on Revenue & Sales Performance

Suburban locations (2.64) have the highest average price level, suggesting customers in these areas are more willing to pay slightly higher prices, which can drive higher revenue per transaction.

Tourist areas (2.61) show moderately high pricing, indicating that visitors accept premium pricing, likely supporting strong revenue during peak seasons.

Urban locations (2.61) have the lowest average price level, implying higher price sensitivity and stronger competition, which may lead to higher sales volume but lower margins.

The overall average price level (2.62) shows pricing is fairly consistent across locations, with small variations influencing revenue more through volume than price differences.
# 3.answer
You have a pivot table summarizing the average price level per food category:

Food Item	Average Price Level
BBQ	2.634
Burgers	2.663
Curry	2.596
Pasta	2.604
Pizza	2.604
Salads	2.671
Sushi	2.558
Grand Total	2.619
which is useful for understanding pricing trends.
# 3.Answer
Regression Statistics Multiple R 0.028320586 R Square 0.000802056 0.08% Adjusted R Square 0.000358559 Standard Error 1.136038339 Observations 2255 ANOVA df SS MS F Significance F Regression 1 2.333996016 2.333996016 1.808481764 0.178825824 Residual 2253 2907.683742 1.290583108 Total 2254 2910.017738 Coefficients Standard Error t Stat P-value Lower 95% Upper 95% Lower 95.0% Upper 95.0% Intercept 2.609322441 0.024903303 104.7781681 0 2.560486629 2.658158253 2.560486629 2.658158253 customer_id 0.120562616 0.089651095 1.344798038 0.178825824 -0.055244747 0.29636998 -0.055244747 0.29636998.
According to tthe result in regression,we can see that it is statistically significant since significance F is 0.1 which is a good model so sales is a determinant of the cuisine.
<img width="1590" height="49" alt="image" src="https://github.com/user-attachments/assets/97e3223c-5394-4337-9a52-e523eb1c27fb" />
#4. Answer
Day	Avg Service Quality	Avg Overall Satisfaction
Sun	1.987	3.841
Mon	2.322	3.971
Tue	2.318	4.044
Wed	2.308	3.948
Thu	2.292	4.000
Fri	2.286	3.971
Sat	1.997	3.773
Grand Total	2.220	3.937

Observations:

Service quality peaks during weekdays (Mon–Fri ~2.29–2.32) and dips on weekends (~1.99–1.99).

Customer satisfaction roughly follows the same pattern: higher during weekdays (~3.97–4.04) and lower on weekends (~3.77–3.84).

This suggests a positive relationship: when service quality improves, customer satisfaction also tends to increase.




# Use cases: Sales analysis, menu evaluation, customer behavior, service performance
Tools: Excel, Power BI.
Format: CSV / Excel

I am open for collaboration

Author: Modupe Babalola
