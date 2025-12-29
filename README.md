# Hospitality-Dataset-Food-service-operation-
# Introduction
This dataset contains price list and operational data from food service establishments. It is suitable for analyzing revenue trends, menu performance, customer preferences, and service quality.
# Business Questions
What trends exist in customer preferences across menu categories?
How does pricing impact revenue and overall sales performance?
Can sales and demand be accurately predicted using historical data?
How does service quality affect customer satisfaction and operational performance?
# Answer
Customer Preference Trends by Menu Category.
Row Labels	Average of customer_id
BBQ	0.070063694
Burgers	0.071197411
Curry	0.093167702
Pasta	0.065088757
Pizza	0.062305296
Salads	0.104790419
Sushi	0.072555205
Grand Total	0.077161863
<img width="241" height="181" alt="image" src="https://github.com/user-attachments/assets/418d8ce6-f5e3-4462-8299-17e21cf516e6" />

Salads (0.1048) show the highest average customer engagement, indicating a strong preference—possibly driven by health-conscious choices or lighter meal options.

Curry (0.0932) ranks second, suggesting steady demand for flavorful, hearty meals.

Sushi (0.0726), Burgers (0.0712), and BBQ (0.0701) fall in the mid-range, showing consistent but moderate customer preference.

Pasta (0.0651) and Pizza (0.0623) have the lowest averages, indicating relatively lower preference compared to other categories.

The overall average (0.0772) suggests customer preference is moderately spread, with clear leaders (Salads and Curry).
# 2.answer 
Pricing Impact on Revenue & Sales Performance
Row Labels	Average of price_level
Suburban	2.638601036
Tourist	2.612068966
Urban	2.607048458
Grand Total	2.618625277
<img width="241" height="101" alt="image" src="https://github.com/user-attachments/assets/89db8cc3-6e38-4d75-9b2f-1d4ddb86de8a" />

Suburban locations (2.64) have the highest average price level, suggesting customers in these areas are more willing to pay slightly higher prices, which can drive higher revenue per transaction.

Tourist areas (2.61) show moderately high pricing, indicating that visitors accept premium pricing, likely supporting strong revenue during peak seasons.

Urban locations (2.61) have the lowest average price level, implying higher price sensitivity and stronger competition, which may lead to higher sales volume but lower margins.

The overall average price level (2.62) shows pricing is fairly consistent across locations, with small variations influencing revenue more through volume than price differences.
# 3.answer
You have a pivot table summarizing the average price level per food category:
Row Labels	Average of price_level
BBQ	2.633757962
Burgers	2.663430421
Curry	2.596273292
Pasta	2.603550296
Pizza	2.604361371
Salads	2.670658683
Sushi	2.558359621
Grand Total	2.618625277
<img width="241" height="181" alt="image" src="https://github.com/user-attachments/assets/9b8c3ef8-f9c9-4fc8-8967-ac054379f17b" />

which is useful for understanding pricing trends.

# 3.Answer
SUMMARY OUTPUT								
								
Regression Statistics								
Multiple R	0.028320586							
R Square	0.000802056		0.08%					
Adjusted R Square	0.000358559							
Standard Error	1.136038339							
Observations	2255							
								
ANOVA								
	df	SS	MS	F	Significance F			
Regression	1	2.333996016	2.333996016	1.808481764	0.178825824			
Residual	2253	2907.683742	1.290583108					
Total	2254	2910.017738						
								
	Coefficients	Standard Error	t Stat	P-value	Lower 95%	Upper 95%	Lower 95.0%	Upper 95.0%
Intercept	2.609322441	0.024903303	104.7781681	0	2.560486629	2.658158253	2.560486629	2.658158253
customer_id	0.120562616	0.089651095	1.344798038	0.178825824	-0.055244747	0.29636998	-0.055244747	0.29636998
<img width="1017" height="367" alt="image" src="https://github.com/user-attachments/assets/d9298470-c281-4380-ae01-801420792225" />
According to tthe result in regression,we can see that it is statistically significant since significance F is 0.1 which is a good model so sales is a determinant of the cuisine.
<img width="1590" height="49" alt="image" src="https://github.com/user-attachments/assets/97e3223c-5394-4337-9a52-e523eb1c27fb" />
#4. Answer
Row Labels	Average of service_quality	Average of overall_satisfaction
Sun	1.987012987	3.840909091
Mon	2.321533923	3.970501475
Tue	2.317784257	4.043731778
Wed	2.308139535	3.947674419
Thu	2.292358804	4
Fri	2.286173633	3.971061093
Sat	1.996763754	3.773462783
Grand Total	2.219955654	3.937472284
<img width="469" height="181" alt="image" src="https://github.com/user-attachments/assets/eabacc15-2b1f-4ee1-93f8-f25cfef305ba" />

Service quality peaks during weekdays (Mon–Fri ~2.29–2.32) and dips on weekends (~1.99–1.99).

Customer satisfaction roughly follows the same pattern: higher during weekdays (~3.97–4.04) and lower on weekends (~3.77–3.84).

This suggests a positive relationship: when service quality improves, customer satisfaction also tends to increase.

# Use cases: 
Sales analysis, menu evaluation, customer behavior, service performance
Tools: Excel, Power BI.
Format: CSV / Excel

I am open for collaboration

Author: Modupe Babalola
