# buyingahouseasgenz
Data Manipulation and Analysis of Housing Dataset
Dataset Overview
The dataset consists of housing information, including attributes such as price, area, number of bedrooms, bathrooms, number of stories, parking spaces, and additional features like main road access and guestroom availability. The goal was to analyze the data to uncover trends, distributions, and relationships.

1. Data Manipulation
Sorting
Action: Sorted the dataset by price in descending order.
Reason: Sorting by price highlights the most expensive properties, making it easier to analyze premium housing trends and compare them with lower-cost options.
Filtering
Action: Filtered data to include only properties with more than 2 bedrooms and a price greater than 300,000.
Reason: This focused the analysis on higher-value properties suitable for families or larger groups, filtering out smaller or lower-value homes that might not align with the target audience.
Grouping
Action: Grouped data by stories and calculated the mean price for each category.
Reason: Grouping by stories allowed us to examine how housing prices vary with the number of stories, helping identify trends in pricing across property types.
2. Data Visualization
Box Plot
![image](https://github.com/user-attachments/assets/13ad090d-1ed2-43ab-a9c4-52d57d22933a)

Description: Visualized the distribution of housing prices.
Insight: Revealed price outliers and the general spread, showcasing how prices cluster around certain values.
Pie Chart
![image](https://github.com/user-attachments/assets/5bd4ee3e-2ef8-4c6a-9314-e05ceb8e2f7e)

Description: Displayed the distribution of properties by the number of bedrooms.
Insight: Highlighted which bedroom categories were most common, offering insights into market preferences.
Scatter Plot
![image](https://github.com/user-attachments/assets/c91cc5aa-6d21-44f5-a0a2-eb566b84527c)

Description: Plotted price vs. area.
Insight: Identified a positive correlation between area and price, confirming larger houses tend to cost more.
Histogram
![image](https://github.com/user-attachments/assets/9ddb8aed-863c-448c-ac79-023419c1734b)

Description: Displayed the distribution of housing prices.
Insight: Revealed most properties are in the mid-range price category, with a smaller number of luxury homes.

Key Insights:
Price has the highest correlation with area (0.54), followed by bathrooms (0.52) and stories (0.42).
The number of parking spaces has a weaker but noticeable correlation with price (0.38).
5. Summary of Findings
High-value properties tend to have more stories, larger areas, and multiple bedrooms.
Most properties fall within a mid-range price bracket, indicating market stability.
The strongest predictors of price are area, bathrooms, and stories, providing valuable metrics for valuation models.
Properties with fewer than two bedrooms are uncommon in this dataset, indicating the market focus is on medium-to-large family housing.
6. Future Recommendations
Investigate outlier properties to understand factors driving extreme prices.
Perform a deeper analysis of categorical variables (e.g., furnishing status, guestroom availability) and their impact on pricing.
Use the identified correlations to build predictive models for housing prices.
