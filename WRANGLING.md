**Data Cleaning Steps:**

1. **Room Nights Sold Over Time in Nova Scotia**
- Added cleaning step
- Removed Occupancy Rate (all values equaled 0, not helpful data)
- Changed Month/Year data type from String to Date
- Changed Region data role to Geographic (County)
- Ran Output
  
![Alt text](Room_Nights_Sold_Over_Time_In_Nova_Scotia.png)
**Interpretation:** The graph shows the number of room nights sold in Nova Scotia over time, broken down by different regions. From 2008 to 2019, the number of room nights sold remained fairly steady. In 2020, there was a sharp drop, likely due to the COVID-19 pandemic. After 2021, the numbers quickly increased again and even peaked higher than before. More recently, the numbers have leveled off but remain strong. The Halifax Metro area and Cape Breton seem to make up a big part of the total room nights sold. This chart helps show how tourism and accommodations in Nova Scotia have changed over time, especially during and after the pandemic.

2. **Nova Scotians Engagement**
- Added cleaning step
- Changed Year data type to Date
- Changed Group Weighted % data type from Number (whole) to Number (decimal)
- Changed Table column name to Question
- Ran Output
  
![Alt text](How_Residents_Rate_Seasons.png)
**Interpretation:** The chart shows how residents rate Nova Scotia in terms of offering interesting things to do in different seasons. Summer has the highest rating, with most people rating it as "Excellent" or "Good." Spring, Fall, and Winter have more mixed ratings, with fewer people giving them an "Excellent" rating. Winter has the most "Poor" ratings, meaning many residents feel there are fewer interesting activities during this season. Overall, Nova Scotia is seen as having the most to offer in the summer, while the colder seasons receive more average or negative ratings.

![Alt text](Likelihood_Of_Nova_Scotians_Travelling_In_2024.png)
**Interpretation:** The bar chart shows how likely Nova Scotians are to travel in 2024 to different places. Most people are not likely to travel overseas, to the United States, or to the Caribbean, with "Not at all likely" being the largest group for those destinations. More people are considering traveling within Canada, especially in Atlantic Canada and Nova Scotia. A large number of people are "Very likely" to travel within Nova Scotia, meaning they prefer to stay closer to home rather than travel far.

3. **Tourism Nova Scotia Visitation**
- Clean step
- Changed Month/Year data type from String to Date
- Grouped duplicates from visitor origin and country
- Ran Output
  
![Alt text](Domestic_Nova_Scotia_Visitor_Origin.png)
**Interpretation:** The pie chart shows where visitors to Nova Scotia come from within Canada. Most visitors are from Atlantic Canada, making up the largest portion. Ontario is the second biggest source of visitors, followed by Western Canada and then Quebec. This means that people from nearby provinces visit Nova Scotia the most, while fewer visitors come from farther parts of the country.

4. **Arrival and Expenditures**
- Clean step
- Removed null field
- Changed Data role to country/region
- Grouped invalid values with matching values from the data role
- Filtered rows with invalid values for the data role
- Changed t31 column to "Tourist arrival and expenditures"
- Changed "Tourist arrival and expenditures" to Region
- Changed F3 to Year
- Changed Year data role to date
- Excluded Series value in F4
- Deleted F5 column
- Deleted F9 column
- Changed first column name to Expenditures
- Changed F7 column name to Arrivals
- Deleted F4
- Sorted columns
- Ran output
  
![Alt text](International_Visitor_Expenditures.png)
**Interpretation:** The chart shows how much money international visitors spent in Nova Scotia over different years. Each dot represents a country, and the higher the dot, the more money visitors from that country spent. The box plots show the overall spending patterns for each year. The United States stands out as the biggest spender, with much higher amounts compared to other countries. Spending changes over time, with some years seeing bigger amounts, like around 2010 and 2022. The drop in 2020 and 2021 suggests the impact of the COVID-19 pandemic, but spending seems to rise again in 2022. Many different countries continue to visit Nova Scotia, showing that it remains a popular travel destination.
