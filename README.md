# Accident Trend Monitor Dashboard

Welcome to the Accident Trend Monitor Dashboard project! This dashboard is designed to provide insightful visualizations and analysis of road accident data for the years 2021 and 2022. The goal of this project is to help users understand accident trends, casualty distribution, and various factors influencing road accidents.

![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/05d3f34f-0cff-40c0-8af8-253741e0d28a)




## Project Overview & Dashboard Requirement

The Accident Trend Monitor Dashboard focuses on the following key aspects:
- Primary KPI: Total Casualties after the accident
- Primary KPIs: Total Casualties & Percentage by Accident Severity and Maximum Casualties by Type of Vehicle

![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/43dcc56a-fc91-4ae8-a8e0-4189f1650dd6)

  
- Secondary KPIs:
  - Total Casualties by Vehicle Type
  - Monthly Trends Comparison for 2021 and 2022
  - Maximum Casualties by Road Type
  - Distribution of Total Casualties by Road Surface
  - Relationship between Casualties by Area/Location and by Day/Night
  - Casualties by Weather Conditions
  
![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/2a46e5ca-7aac-446d-a9fc-a34fa308a25e)

## Workflow

### Data Cleaning

Data cleaning was performed directly in Excel, involving the following steps:
- Merged similar parameters in the `Junction_Control` and `Accident_Severity` columns.
- Handled blank entries in columns like `Carriageway_Hazards`, `Road_Surface_Conditions`, etc.

### Data Preprocessing

Data preprocessing was also done in Excel:
- Created additional columns for `Year` and `Month` by extracting information from the `Accident Date` column.

### Data Analysis

The analysis was carried out using pivot tables in Excel:
- Calculated metrics for various aspects, including accident severity, vehicle type, monthly trends, road type, road surface, area type, and weather conditions.

### Data Visualization

The insights from the data analysis were visualized using Excel's charting capabilities:
- Pie chart for **Casualties by Urban/Rural Area** to illustrate the distribution of casualties based on whether the accident occurred in an urban or rural area.
  
  ![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/466a53d8-7609-4279-91d9-02085e106c98)

- Pie chart for **Casualties by Day/Night** to compare casualties occurring during the day and night.
  
  ![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/1da0c38f-6c79-499d-99cc-6844d6a00d23)

- Donut chart for **Casualties by Weather Conditions** showcasing casualties based on weather conditions, including rain, fine weather, others, and snow.
  
  ![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/76dcb1a8-a947-4fc2-adae-182f35328bf7)

- Line chart for **Monthly Casualties Comparison (2021 vs 2022)** depicting the monthly trend comparison of casualties between 2021 and 2022.
  
  ![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/472e0ead-82bd-490a-912a-3c465835fe37)

- Bar chart for **Casualties by Road Surfaces** presenting the distribution of casualties across different road surface conditions.
  
  ![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/b75ae221-b377-481a-b4a2-b5688ab66516)

- Column chart for **Road Type vs Casualties** showing casualties based on different road types.
  
![image](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/d68843ea-9a21-4f5b-9b82-7029f3753b9e)

### Dashboard Creation

![DASHBOARD](https://github.com/ipratham7/Accident-Trend-Monitor/assets/64377030/cc91118e-ce6f-4002-90f6-33330772d101)

A comprehensive dashboard named "Accident Trend Monitor" was created directly in Excel:
- All visualizations were organized in the dashboard sheet.
- Slicers were added to allow users to filter data by date timeline and urban vs. rural areas.

## Project Description

The dashboard provides a user-friendly interface to explore and understand road accident trends. The primary KPIs offer insights into the overall impact of accidents, while secondary KPIs delve deeper into factors such as vehicle type, road conditions, and time of day. The intuitive visualizations help stakeholders gain actionable insights, assisting decision-making for road safety improvements.

## How to Use

1. Download the Excel file containing the dashboard.
2. Open the Excel file and navigate to the "DASHBOARD" sheet.
3. Use the slicers to interact with the data and customize the visualizations.
4. Explore the dashboard to gain insights into road accident trends.

## Project Structure

- `Main Project.xlsx`: Excel file containing the dashboard, data, and visualizations.
- `README.md`: This file, providing an overview of the project.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements or additional analyses, feel free to create a pull request or open an issue.

## Contact Me

If you have any questions, suggestions, or feedback regarding this project, feel free to contact me at prathamkataria99@gmail.com 

