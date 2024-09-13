## Executive Summary
<div align='justify'>
This project outlines Cars4U's initiative to develop a robust pricing model for the used car market. By utilizing advanced machine learning techniques, the company aims to optimize pricing strategies and enhance market positioning.<br>
The GradientBoostingRegressor model, developed using data up to 2019, serves as a solid foundation and has the flexibility to incorporate current market trends. The model was built with data limited to entry-level and mid-tier price ranges as they show better market consistency than luxury cars. While the proposed model demonstrates good performance, considering the high variation in prices in the used car market, there is still room for improvement. Future enhancements should include:
</div>

1.	Integrating up-to-date data.
2.	Adding more predictive features.
3.	Ensuring high-quality new data.
4.	Segmenting cars into different price ranges to create more tailored marketing and sales strategies.

<div align='justify'>
To maximize the model's potential and profitability, it is advisable to address all these aspects.
</div>

### Problem summary:  
<div align='justify'>
<p> 
Recent trends in the Indian car market indicate a notable shift from new car purchases to pre-owned vehicles. Although both segments are growing, the surge in the popularity of used cars is particularly significant, with sales projected to reach <b>8.2 million</b> units by FY2025 [1, 2].
</p>

<p align='center'>
<img src='https://github.com/Gr3Fin/DA_projects/blob/main/Used_Car_Prices/images/sales_used_new.png' title='sales new vs used cars'>
</p>

<p>
This business potential has been recognized by major players such as <b>Suzuki, Mahindra, Volkswagen, Audi, BMW</b>, and <b>Porsche</b> [1, 3, 5] as well as by online automotive marketplaces like <b>OLX Autos</b> or <b>CarTrade</b>, which number is increasing rapidly across India.<br>
Currently, the majority of transactions in the used car market are informal, with only 17% to 25% of the market being organized. However, this organized segment is expected to expand to <b>45%</b> by FY2025 [1, 3, 4], presenting substantial opportunities for new businesses, especially that technological advancements and digitalization has already made buying and selling used cars more accessible and trustworthy [2, 3, 4].<br>
High competition in this area requires solid tools that help gain an advantage in the market.
</p>
<p>
A critical challenge for new entrants, though, is determining the optimal pricing strategy to ensure profitability. Pricing used cars is particularly complex due to the numerous factors influencing their value. Therefore, the key objective of this project is to <b>build a predictive model for used car prices</b> in India to optimize pricing strategies and enhance business profitability.
<p>
The regression model developed in this study aims to provide insights into:
<ul>
    <li><b>Feature Identification:</b> Recognize the features that most significantly impact the final price.</li>
	<li><b>Model Accuracy:</b> Build a predictive model with high accuracy in car price estimation.</li>
</ul>    
</p>
<p>
The analysis and model predictions discussed will assist the company in:
<ul>
    <li>Developing effective business strategies,</li>
	<li>Managing inventory efficiently,</li>
    <li>Supporting strategic decision-making,</li>
	<li>Optimizing revenue.</li>
</ul>
</p>
<p>
By addressing these areas, the company can create a competitive edge in the market.
</p>
</div>

### Recommendations for Further analysis:

**Potential for Model Improvement**  

<div alignment='justify'>
The current model for predicting used car prices performs well and serves as a reliable tool for market orientation. However, there are opportunities for further refinement and improvement. To enhance the model’s accuracy and reliability, the following recommendations are proposed:
</div>
<ol>
    <li>Incorporate up-to-date data</li>
    <li>Capturing more variability in target prices</li>
    <li>Implementing cutting-edge technology</li>
</ol>

### Recommendations for Business and Implementation:

<ul>
    <li>Market Segmentation and Consumer Preferences</li>
    <li>Focus on High-Impact Features</li>
    <li>Tailor Marketing Strategies</li>
    <li>Price Adjustment Mechanism</li>
    <li>Enhance Customer Experience</li>
    <li>Future Trends Monitoring</li>
</ul>

### Bibliography
1.	[Autocar India](https://www.autocarindia.com/car-news/used-car-market-to-be-twice-as-big-as-new-car-segment-by-fy2025-421140)
2.	[HT Auto](https://auto.hindustantimes.com/auto/cars/whats-pushing-india-s-used-car-market-explained-here-41640687279207.html)
3.	[Mordor Intelligence](https://www.mordorintelligence.com/industry-reports/india-used-car-market/market-trends)
4.	[LeadSquared](https://www.leadsquared.com/industries/automotive/used-car-market-trends/)
5.	[6Wresearch](https://www.6wresearch.com/industry-report/india-used-car-market-2020-2026)
6.	[CarWale](https://www.carwale.com/)
7.	[CarDekho](https://www.cardekho.com/)
8.	[ZigWheels](https://www.zigwheels.com/)
