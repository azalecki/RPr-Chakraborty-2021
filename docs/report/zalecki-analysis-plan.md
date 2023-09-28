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

4. Mapping Residuals to Test Independence Assumptions
***Analysis***
In Chakraborty's study, generalized estimating equations (GEEs) were used to conduct a multivariate analysis of the disability subgroups and the socio-demographic categories. Clusters were pre-defined by state and by significant clusters of Covid-19 cases. It is assumed in the study that there is a possible correlation within the clusters (for example, within the same state). However, the GEE models also assume independence which means that there is no important correlation between clusters. My question is: 
How do we know that the clusters are independent of eachother? 
***Visualization***
I will attempt to answer this question by mapping the errors and clusters of overestimates. By anayzing the map visualization we can look at the cluster of overestimates of errors and see if they cross over any state boundaries. 
***Discussion***
If my new/revised map shows clusters of overestimates crossing over state boundaries, it will mean that we cannot fully assume that the clusters are independent of eachother

5. Integration of Discussion Section
***Analysis*** 
Integrate Emily's discussion section with any new results that have not yet been discussed. 

6. Additional Conclusion 
***Analysis***
Write a seperate conclusion section that concludes whether the reproduction attempt was successful and what the implications are for how the original study contributes to scientific knowledge. 
