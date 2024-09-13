## Executive Summary

### Problem summary
<div align= "justify">
The primary objective of this project was to predict housing prices in various suburbs or towns in Boston based on specific locality features. This involved addressing two critical questions:
  
1.	**Accuracy of Predictions:** How accurately can we predict housing prices based on the provided criteria?
2.	**Influential Factors:** What are the key factors that significantly influence housing prices?

By answering these questions, the client will gain valuable insights into potential future investment returns and will be better equipped to identify promising opportunities as well as potential risks.  

To achieve the objective, I have analyzed data that included information about crime statistics, residential lands zoned for lots, presence of industrial businesses, Charles River in the neighbor, 
air pollution, average rooms number in properties, buildings age, distances to Boston employment centers, accessibility to radial highways, property-tax rates, pupil-teacher ratios, 
percentage of lower status population in the area and median value of homes occupied by owners.  

The dataset included approximately 500 records. To complete the task, I developed several regression models to find the one that fulfills the following goals:
-	**Accurate Predictions:** Predict housing prices for unseen data with the highest possible accuracy.
-	**Variable Influence:** Understand how different variables affect housing prices.

To evaluate the models’ performance, I used metrics like RMSE, MAE, MPAE, and R2. This allowed me to compare different solutions and select the best one. I have also implemented 
cross-validation techniques to check if the selected models perform well on new data.
</div>

### Conclusions:
<div align= "justify">

  1.	**Target High-Impact Features:**
-	**LSTAT (Percentage of Lower Status Population):** This feature has the highest negative impact on MEDV. Reducing the percentage of lower status residents through community programs, education, and economic development could significantly increase property values.
-	**RM (Average Number of Rooms per Dwelling):** This has the highest positive impact. Encouraging or facilitating the construction of homes with more rooms could boost property values.
-	**NOX (Nitric Oxides Concentration):** This has a substantial negative impact. Efforts to reduce pollution and improve air quality could positively influence property values.
-	**CRIM (Per Capita Crime Rate):** This negatively impacts property values. Implementing effective crime reduction strategies could lead to higher property values.

2.	**Monitor Moderate-Impact Features:**
-	**DIS (Weighted Distance to Employment Centers):** While the impact is moderate and negative, improving transportation infrastructure to reduce travel time to employment hubs could have a beneficial effect.
-	**PTRATIO (Pupil-Teacher Ratio):** This also has a moderate negative impact. Enhancing educational resources and reducing the pupil-teacher ratio in schools could improve property values.
-	**RAD (Index of Accessibility to Radial Highways):** This feature has a moderate impact and is slightly positive. Ensuring good accessibility while balancing other factors like noise pollution could be beneficial.

3.	**Negligible Impact Features:**
-	**CHAS (Proximity to Charles River):** This feature has a negligible impact on property values. Investments related to the proximity to the river may not yield significant returns in terms of property value increase.
</div>

### Recommendations:
<div align= "justify">
  
1.	**Community:**
-	Implement socio-economic improvement programs targeting lower-status populations to enhance their living conditions.
-	Invest in local businesses, create job opportunities and indirectly increase property values.
  
2.	**Housing Development:**
-	Promote the construction of larger homes with more rooms to attract higher home values by attracting higher-income residents.
-	Balance development by including affordable housing to ensure a diverse and inclusive community.
  
3.	**Environmental Policies:**
-	Work with local government to strengthen environmental regulations to reduce NOX emissions and improve air quality contributing to higher property values.
-	Promote green energy initiatives.
-	Increase the number of parks and green spaces to improve air quality and make neighborhoods more attractive.
  
4.	**Educational Investments:**
-	Advocate for increased funding for schools to lower the pupil-teacher ratio, thereby making the area more attractive for families and increasing property values.
-	Support local schools with extracurricular programs and tutoring services to enhance educational outcomes.

5.	**Crime Reduction:**
-	Develop comprehensive crime reduction strategies to improve community safety and attractiveness.
-	Create environments that discourage criminal activity through urban planning, invest in security systems, improve street lighting
- Implementing programs aimed at reducing crime rates.

6.	**Transportation and Infrastructure:**
-	Invest in transportation infrastructure to reduce commute times to employment centers and improve accessibility to highways, enhancing the desirability of the area.
-	Invest in better road maintenance and expanding public transport routes.

7.	**Resource Allocation:**
-	Focus resources on impactful areas such as socio-economic improvement, housing development, education, and environmental quality rather than on proximity to the river, which has a negligible impact.
-	On the other hand, it is important to recognize the potential benefits offered by natural surroundings. Promoting the development of recreational and commercial amenities near the Charles River can be beneficial for enhancing the attractiveness of nearby properties.
</div>
