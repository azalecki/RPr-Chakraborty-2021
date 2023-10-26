# Planned revisions to reproduction of Chakraborty 
Author: Ola, Zalecki

Created September 28, 2023

## List of changes 

1. Update Chloropleth Map 
***Analysis***
Update the last chloropleth map in the report that visualized the Race Model Weights by county. Within the code there seems to be a mistaken parameter that is only using half of the available color ramp. The map is not only difficult to interpret but also possibly misleading because it makes it seem like all of the counties are a higher weight than they are. 
***Visualization***
The improved map will have a greater variation in shade between the lowest and highest values meaning that the lower values will have a less saturated orange color and vice versa.

2. Move Rationale Section
***Analysis***
Move the code for "rationale for the updated report" section to the end. It makes more sense in terms of reading flow for it to be at the end. Later, when processing the report this section will be located at the end. 

3. Missing Data Table
***Analysis*** 
Improve the missing data table with Kable and/or KableExtra functions as well as transpose the table to a verticle orientation. At the moment the table is missing data and is difficult to read. There are more columns than rows so in order to make the table more readable, I will transpose it to a vertical position. 
***Visualization***
The improved table will contain the correct data and be in a vertical position.

4. Mapping Residuals of Race 
***Analysis***
In the reproduction of Chakraborty's study, a map of Race Model Residuals was generated to observe the differences between observed and predicted values from the gee model. There was only one map made for the model that corrected for Covid Incidence Rate. I am curious to see the spatial distribution of error for the other 3 models from the reproduction. I beliece this will help us assess the quality of the model and consider its future use. 

***Visualization***
I will visualize this data by first calculating the residuals with the data from the 3 other models: "Switch to R Geepack", "SatScan Gini Optimized Clusters", and "Spatial EPI Clusters." Then I will generate 3 national level maps of their residuals resembling the Race Model Residuals map. By anayzing the map visualization we can observe how different models under/over predict outcomes.  
***Discussion***
If the new maps show dispraportionate over/under estimates in certain areas of the country that would be a cause for concern. Ideally, the models should aim to predict values as close to the observed values to assume correctness. If they don't we might need to consider making some changes to the models in order to fix the over/under estimates. 

5. Integration of Discussion Section
***Analysis*** 
Integrate Emily's discussion section with any new results that have not yet been discussed. 

6. Additional Conclusion 
***Analysis***
Write a seperate conclusion section that concludes whether the reproduction attempt was successful and what the implications are for how the original study contributes to scientific knowledge. 
