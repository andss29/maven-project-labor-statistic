# Maven Career: Interactive Dashboard to Guide High School Seniors in Career Exploration

This repository contains an Excel-based U.S Labos Statistic trend Dashboard that can support high school seniors in making informed career decisions. The dashboard allows users to explore employment and wage trends across industries and states, enabling comparisons and insights that align with their interests and goals.

![Screenshot 2025-06-17 233455](https://github.com/user-attachments/assets/63664189-710a-476b-a6a9-3673192da333)

**Data Summary:** U.S. Labor Statistics (2017–2020) covering Year, Industry, and State as dimensions. Measures include Number of Establishments, Employees, and Avg. Annual Wage.
**Tool Used:** Microsoft Excel
**Data Transformation:** I used formula like UNIQUE, SUMIFS, AVERAGEIFS, and VLOOKUP to clean and extract insights from raw labor data
**Dashboard Design:** Created an interactive dashboard with custom charts, filter, data typing, and dynamic highlights for better clarity. 


# Features:
**Interactive Filter by Industry**: The filter allows users to filter the industry based on their preference
For this, I used data validation to create a dropdown list of industries, then I used the Spin Control (form control) to allow user select the industry.

![image](https://github.com/user-attachments/assets/5a109ebf-d527-42bd-9c91-c51a01ef1434)

**Interactive Map Filter:** The filter allows users to explore Average Wage and Employee per 1,000 in all the states in the U.S.
For this, I generated population data from Excel from every states, then I created costumized metrics for Employees per 1,000 capita and using AVERAGEIFS to calculate the Avg. Wage. I used Option Button (form control) to allow user select the map category.

![image](https://github.com/user-attachments/assets/67c0f040-9b1b-4560-bc5f-e954d583b792)


_Note:_ For both filter,  I applied the INDEX and IF function to make the selection linked it back to the prep and raw data for automatic updates. 


**Goal of this project:**

The primary goal of this dashboard was to support high school seniors in making informed career decisions by building an interactive data dashboard. The dashboard
allows users to explore employment and wage trends across industries and states, enabling comparisons and insights that align with their interests and goals.

**Student Use Cases:**
Career Exploration Support – Help to discover industries with strong wage potential and employment growth.
Informed Decision-Making – Enable comparison of industries and states to align career interests with real-world data.

**Personal goals:**
Skill Development – Demonstrate the use of Excel’s advanced analytical functions and dashboarding capabilities.
Data Accessibility – Present complex labor data in a format that is engaging and easy to navigate for a non-technical audience.
Customization & Interaction – Allow students to personalize their career search experience using dynamic filters and visual feedback.


