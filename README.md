# Real-time Weather Dashboard using Power BI

![Dashboard Screenshot](https://user-images.githubusercontent.com/109890466/232371997-767d2645-4203-455b-80a5-29653a921d7b.png)

## Overview

This project is a dynamic and interactive weather dashboard built with Microsoft Power BI. It provides real-time weather data for any location, leveraging a live weather API. The dashboard is designed to be clean, user-friendly, and insightful, offering a comprehensive view of current weather conditions and a 7-day forecast.

Data is automatically fetched, cleaned, and updated to ensure the information is always current, making it a powerful tool for live weather tracking.

## Key Features

*   **Live Data Integration**: Connects to a real-time weather API to fetch up-to-the-minute weather data.
*   **Automated Data Refresh**: Utilizes Power Automate to trigger seamless, real-time updates without manual intervention.
*   **Data Transformation**: Employs Power Query for efficient data cleaning, shaping, and transformation to ensure data quality and consistency.
*   **Interactive Visuals**: Features a clean, interactive dashboard with slicers and dynamic DAX measures for a customized user experience.
*   **Comprehensive KPIs**: Displays key performance indicators (KPIs) for a complete weather analysis.
*   **7-Day Forecast**: Provides a detailed weather forecast for the upcoming week.

## Key Performance Indicators (KPIs) Displayed

*   **Current Weather Conditions**: (e.g., Sunny, Cloudy, Rain)
*   **Temperature**: Current, maximum, and minimum.
*   **Atmospheric Pressure**: Measured in hPa.
*   **Wind Speed & Direction**: Real-time wind analysis.
*   **UV Index**: Current ultraviolet radiation level.
*   **Humidity**: Percentage of moisture in the air.
*   **Visibility**: Distance one can see clearly.
*   **Sunrise & Sunset Times**: Daily solar timings.

## Technologies Used

*   **Data Visualization & Dashboarding**: Microsoft Power BI
*   **Data Transformation & Cleaning**: Power Query
*   **Workflow Automation**: Power Automate
*   **Data Modeling & Calculations**: Data Analysis Expressions (DAX)
*   **Data Source**: Live Weather API

## How It Works

1.  **API Data Fetch**: A live weather API is used as the primary data source.
2.  **Data Transformation with Power Query**: Raw JSON data from the API is loaded into Power BI, where Power Query is used to parse, clean, and structure the data into a usable format.
3.  **DAX Measures**: DAX is used to create calculated measures for the KPIs and to enable complex filtering and interactions within the dashboard.
4.  **Interactive Dashboard Design**: The cleaned data and DAX measures are visualized on the Power BI canvas to create an intuitive and interactive report.
5.  **Automated Refresh with Power Automate**: A Power Automate flow is set up to automatically refresh the Power BI dataset, ensuring the dashboard always displays the latest weather information.

## Author

*   **Yash Pardhi**
    *   GitHub: [yashpardhi2403](https://github.com/yashpardhi2403)

