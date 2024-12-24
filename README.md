# Students-Survey-

### Dashboard Link :https://dnyanamcoachingcenter-my.sharepoint.com/:u:/g/personal/priyaauti_dnyanamcoachingcenter_onmicrosoft_com/EXXgX40bZEBAuqra5jmJc7MB8XAUKv9AtkbrSr9U617MGQ?e=bE48ez
## Problem Statement


The purpose of this dashboard is to extract meaningful insights from the survey conducted in various stores across the United States. The survey focuses on the spending habits of students in different categories like Video Games, Indoor Games, Toys, Books, Gadgets, etc. It also categorizes stores based on their location and setting.

This dashboard will help identify the total amount of purchases made by students in different store settings and locations, analyze the spending habits based on various factors like age.


### Steps followed 

- Step 1 : Loaded data into Power BI Desktop from the provided Excel file (`Student Survey` and `User Mappings` tables).
- Step 2 : Cleaned and transformed the data using Power Query to ensure consistency and proper data types.
- Step 3 : Created various visualizations to represent spending habits, focusing on metrics like Total Amount of Purchases (TAP), Video Games, Outdoor Sports, etc.
- Step 4 : Applied conditional formatting to the Total Amount of Purchases based on the specified TAP thresholds (Red for TAP < 35000, Yellow for TAP between 35000 and 60000, and Blue for TAP >= 60000).
- Step 5 : Used a Matrix Visualization to show the amount spent on Outdoor Sports across different ages and store settings, with color formatting based on the amount spent.
- Step 6 : Designed a Funnel Chart to display the Total Amount of Purchases by Store Setting, showing data labels as percentages of the first value.
- Step 7 :  Created a Pie Chart to visualize the total amount of purchases by Store Location for the Suburban Store Setting only, using the filter context to focus on Suburban data 
- Step 8 : Developed Scatter Plots and Sand Dance plots to show relationships between various types of purchases (Video Games, Outdoor Sports, Indoor Sports) across different age groups.
- Step 9 : Published the report to Power BI Cloud Service and created a Master Dashboard consisting of the Funnel Chart and Scatter Plots.
- Step 10 : Used the Q&A feature of Power BI to generate insights on average student age and the total amount of purchases by Store Location, visualized in a Donut Chart.


### Snapshot of the Power BI Dashboard (Power BI Service)

![Screenshot 2024-12-24 221626](https://github.com/user-attachments/assets/9bf6b439-8a37-408c-a571-44b03390baf8)



### Insights

- **Total Number of Students Surveyed** = X (You can calculate the total number of students from the dataset)
  
#### Key Insights from the Data:

1. **Total Amount of Purchases (TAP) by Store Setting**:
   - Stores in **Suburb settings** have a significantly higher TAP than those in **Rural** or **Suburban** areas.
   
2. **Age Group Spending**:
   - Students between the ages of **8-22** have the highest spending on **Outdoor Sports** and **Video Games**.
   
3. **Store Location Analysis**:
   - Most spending occurred in **Suburban**, followed by **Urban**, with **Rural locations** showing the least expenditure.

4. **Average Age of Students**:
   - The average age of students surveyed is calculated using the Q&A feature and displayed on the dashboard.

5 **Purchase Category Insights**:
   - **Video Games** have the highest average spending, followed by **Outdoor Sports Kits**.
