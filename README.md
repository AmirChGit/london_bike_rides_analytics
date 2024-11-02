London Bike-Sharing Data Analysis with Tableau
![image](https://github.com/user-attachments/assets/4cd49f72-15a0-4ae0-9446-0891ee817ad4)

==============================================

This project showcases a dynamic and visually engaging Tableau dashboard that provides valuable insights into London’s bike-sharing trends. By leveraging a robust data analysis pipeline, the project efficiently processes and visualizes data, offering an interactive experience for exploring various factors that impact bike usage.

----------------------------------------------
Table of Contents
----------------------------------------------
1. Project Overview
2. Data Acquisition and Exploration
3. Data Manipulation and Preparation
4. Tableau Dashboard
5. Dashboard Features and Interactivity
6. Visualizations
7. Conclusion

----------------------------------------------
1. Project Overview
----------------------------------------------
This project aims to deliver a comprehensive data analysis using the London bike-sharing dataset. The end result is an insightful Tableau dashboard that enables users to explore data trends and relationships interactively. The workflow involves data acquisition, preparation, and the creation of visualizations that make complex data accessible and actionable.

----------------------------------------------
2. Data Acquisition and Exploration
----------------------------------------------
2.1 Data Download
The London bike-sharing dataset is programmatically downloaded using the Kaggle API, ensuring up-to-date and efficient data retrieval without manual intervention.

2.2 Data Exploration
Using Python and the pandas library, the data is examined to understand its structure and key components:
- Analysis of columns and their significance.
- Identification of unique values in important fields such as weather codes and seasons.

----------------------------------------------
3. Data Manipulation and Preparation
----------------------------------------------
3.1 Column Renaming and Adjustments
To enhance readability and usability:
- Columns are renamed to more descriptive labels.
- Humidity values are converted to percentages for a clearer understanding.

3.2 Mapping Numerical Values
Numerical codes representing seasons and weather conditions are mapped to their corresponding textual descriptions, making the data more user-friendly.

The refined dataset is then exported to an Excel file, ready for visualization in Tableau.

----------------------------------------------
4. Tableau Dashboard
----------------------------------------------
The Tableau dashboard is the centerpiece of the project, built to provide an immersive data exploration experience. It connects to the processed dataset and features interactive elements that reveal bike-sharing patterns in London.

----------------------------------------------
5. Dashboard Features and Interactivity
----------------------------------------------
5.1 User-Defined Parameters
Two key parameters are included to give users control over the data analysis:
- **Moving Average Period**: Adjusts the time period for moving average calculations.
- **Moving Average Duration**: Specifies the duration of the moving average.

5.2 Set Actions
The dashboard utilizes set actions to enhance interactivity:
- Users can select different time intervals on the moving average chart, dynamically updating other elements of the dashboard to reflect changes.

5.3 Filtering Options
An intuitive filter allows users to modify the displayed time range, making data exploration flexible and tailored to their needs.

----------------------------------------------
6. Visualizations
----------------------------------------------
The following visualizations are created for a comprehensive analysis:

1. **Total Number of Bike Rides**
   - A chart depicting the total number of bike rides between selected time periods.

2. **Moving Average Chart**
   - The main visualization displaying the moving average of bike rides over time, customizable with user-defined parameters.

3. **Temperature vs. Wind Speed Heat Map**
   - A heat map illustrating the relationship between temperature and wind speed.

4. **Total Bike Rides by Weather (Tooltip)**
   - A detailed breakdown of bike rides by weather conditions, displayed through an interactive tooltip.

5. **Total Bike Rides by Hour (Tooltip)**
   - A visualization within a tooltip, showing bike rides distributed by the hour of the day.

----------------------------------------------
7. Conclusion
----------------------------------------------
This project delivers a hands-on approach to data analysis and visualization. By effectively using data manipulation techniques and Tableau's capabilities, it provides an insightful look into bike-sharing trends. The interactive dashboard empowers users to explore data in meaningful ways, revealing key insights into how various factors influence bike usage in London.
