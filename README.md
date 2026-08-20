This was a small, day long project, where I analyzed data from seweratlas.com to see if there was a correlation between the population of an area, the LULC characteristics of the area
and the amount of virus in the wastewater therein. I began by taking data from the facilities that all of the tables had in common, then taking the average of the multitudes of entries for the 
virus. After some data handling I created a correlation matrix heatmap, and after inspecting said graph, took the 5 most impactful variables and created variable vs virus graphs. I then fed 
those 5 variables into a linear regression model, just to make sure that there was indeed a pattern between the elements. Then I finally made an Actual vs. Predicted graph, and called it quits.
I noticed that there was indeed a moderate influence between the amount of people in an area and the amount of virus in it, however it wasn't what I thought it would be. The trend that the graph 
calculated was that the less people that were in an area, the more virus would be there. It might be because higher concentrations of people lead to better facilities and circumstances. Some of 
the limitations of this small project, was the lack of large datasets. Seweratlas is a generally new database, and as such, after taking common facilities, I only had 31 values for each variable. 
I could've also used more types of data, instead of just population and LULC, having environmental variables around a plant would've been interesting, and could've led to a more stand-out result.
Again, the datasets are not in the jupyter notebook, but the datasets are on seweratlas.com specifically the Wastewater Viral Activity Levels, Plant Population Statistics, and Plant Land Use 
/ Land Cover Statistics tables.
