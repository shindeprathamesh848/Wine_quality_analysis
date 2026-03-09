The Wine Quality dataset contains information on red and white wine samples. This dataset aims to classify the quality of the wine based on chemical properties like pH, density, alcohol content and citric acid content.


The common variables included in this Excel dataset:


· Fixed Acidity - The number of fixed acids in the wine, expressed in g/dm^3.

· Volatile Acidity - The number of volatile acids in the wine, expressed in g/dm^3.

· Citric Acid - The amount of citric acid in the wine, expressed in g/dm^3.

· Residual Sugar - The amount of residual sugar in the wine, expressed in g/dm^3

· Chlorides - The amount of chloride in the wine, expressed in g/dm^3.

· Free Sulfur Dioxide - The amount of free sulfur dioxide in the wine, expressed in mg/dm^3.

· Total Sulfur Dioxide - The amount of total sulfur dioxide in the wine, expressed in mg/dm^3.

· Density - The density of the wine, expressed in g/cm^3.

· pH - The pH level of the wine.

· Sulphates - The number of sulphates in the wine, expressed in g/dm^3.

· Alcohol - The alcohol content of the wine, expressed in % vol.

· Quality - The quality rating of the wine, on a scale of 0 to 10.




Questions:


Section 1: Data Understanding & Cleaning

1. Import the dataset into Excel and convert it into an Excel Table.

a. What advantages does using a table provide for analysis?

2. Identify and highlight duplicate rows in the dataset using conditional formatting.

3. Check whether any columns contain missing or blank values.

a. Count the number of missing values for each variable.

4. Standardize the number format for all chemical variables to show 2 decimal places.


Section 2: Basic Data Analysis

5. Calculate the following statistics for each numeric variable using formulas:

a. Average

b. Median

c. Standard Deviation

d. Minimum

e. Maximum

6. Create a new column called "Quality Category" using an IF formula:

a. Quality ≤ 4 → Low

b. Quality 5–6 → Medium

c. Quality ≥ 7 → High


7. or PivotTables.

8. Determine the percentage of wines in each quality category.


Section 3: Conditional Analysis

9. Highlight wines with:

a. Alcohol > 12%

b. pH < 3.2

c. Volatile acidity > 0.6 using conditional formatting.

10. Create a formula to identify wines with high acidity risk if:

· Fixed Acidity > average AND

· pH < average.


Section 4: Advanced Functions

11. Create a Quality Score Index using the formula:

Score=(Alcohol×2)+(Sulphates×1.5)−(VolatileAcidity×2)Score = (Alcohol × 2) + (Sulphates × 1.5) - (Volatile Acidity × 2)Score=(Alcohol×2)+(Sulphates×1.5)−(VolatileAcidity×2)

Then rank wines based on this score using the RANK function.

12. Use XLOOKUP or INDEX-MATCH to retrieve the Alcohol value of the top-ranked wine.

13. Create a formula to calculate the difference between total sulfur dioxide and free sulfur dioxide.

14. Use the CORREL function to determine the correlation between:

· Alcohol and Quality

· pH and Quality

· Volatile Acidity and Quality.


Section 5: Pivot Table Analysis

15. Create a Pivot Table showing:

· Average Alcohol by Quality Category.

16. Create another Pivot Table to analyze:

· Average pH by Quality.

17. Create a Pivot Table that shows:

· Count of wines by Quality Category.

18. Create a Pivot Table that compares:

· Average Citric Acid and Volatile Acidity across Quality levels.


Section 6: Data Visualization

19. Create the following charts:

· Histogram of Alcohol content

· Scatter Plot: Alcohol vs Quality

· Box Plot (or similar) for pH distribution by Quality.

20. Create a chart showing average alcohol content by quality category.

21. Create a scatter plot showing the relationship between volatile acidity and quality.


Section 7: Dashboard Creation

22. Build an interactive Wine Quality Dashboard containing:

KPIs

· Total Wines

· Average Alcohol

· Average pH

· Average Quality Score

Charts

· Quality distribution

· Alcohol vs Quality

· Average chemical properties by quality

Filters (Slicers)

· Quality Category

23. Add dynamic slicers that allow the dashboard to update based on selected Quality Category.

24. Create a Top 10 wines analysis section showing wines with the highest predicted score.

25. Add a summary insight box that automatically displays:

· Highest alcohol value

· Lowest pH

· Most common quality category.
