# Bike Purchasing Customer Analysis

## Overview:
The goal of this project is to analyze the demographics and  behavior of customers who purchase bikes and to develop data-driven decision making for business growth and customer satisfaction. I explored key metrics such as average income, age distribution, and commute distance.

The full Google Sheets project can be viewed [here](https://docs.google.com/spreadsheets/d/1lnW-6IZPMa3qBn5QJgeDVPCk4sQG6SL7U_bOiHMNmsk/edit?usp=sharing)

## Objectives:
Analyze the average income of bike purchasers to understand the purchasing power of our customer base.
Explore the age distribution of bike purchasers to identify target demographics for tailored marketing efforts.
Investigate customer commute distance to assess its correlation with bike purchasing behavior 
Utilize data-driven insights to make informed decisions aimed at fostering business growth and enhancing customer satisfaction.

## Analysis:
To get a clearer picture of the age demographic, I categorized age into 3 groups and explored how they correlated with the bike purchases. I also calculated average income segmented by gender and bike purchases based on work commute distance.

## Formulas & Functions:
In organizing age groups, I used the IF function. I categorized the ages 0 - 30 as "Adolescent", ages 31 - 54 as "Middle Aged and 55 and above as "Senior". By arranging the data into groups, I obtained a clearer visualization of the age distribution among customers, as opposed to ages being scattered when plotted.

### IF formula used:
=IF(L2>54, "Senior",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))

I rephrased the input "10+ Miles" to "More Than 10 Miles" to ensure proper ascending order in the "Commute" category. This adjustment facilitated an accurate visualization of the commute distribution.

## Visualization:
I was able to visually illustrate the differences in average income across genders through pivot tables and charts. Using pivot tables and line charts, I discovered how commute distance and age impact bike purchasing decisions.

## Insights:
My analysis revealed that the male customers had a higher average income and showed a slightly stronger inclination towards bike purchases compared to their female counterparts. A stronger finding was that shorter work commute distances appeared to be a driving factor in bike purchases. Finally, I observed that there was a preference among middle-aged individuals for bike purchases, with adolescents and seniors significantly lower.

## Recommendations:
- I recommend commute-focused messaging based on my analysis. This is achieved by creating marketing messages highlighting the perks of biking for short commutes. These highlights include convenience, time-saving, and environmental sustainability. Then direct ads to areas abundant with potential customers who commute briefly. 
- My second recommendation would be in regards to middle-aged comfort. This would focus on creating bikes with ergonomic designs and comfortable riding experiences that would appeal to middle-aged customers who prioritize comfort and functionality.
- My last recommendation would involve influencer partnerships.  This would be a collaboration with influencers or ambassadors who resonate with the target demographic, particularly middle-aged males, to promote biking as a lifestyle choice and endorse specific bike models or features.
