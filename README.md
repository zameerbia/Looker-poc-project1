# Looker POC – Project Requirement

## Project Title: Development of a Clinical Performance Dashboard in Looker

### Objective

The primary objective of this project is to evaluate the capabilities of Looker as a data visualization and analytics platform. We aim to create a comprehensive and interactive Clinical Performance Dashboard that showcases some of Looker's features.

### Key Features of the Dashboard

1. **Dashboard Interface**
   - A user-friendly interface with prompts for selecting a specific department by name and a specific month.
   - A clear and intuitive design to enhance the user experience.
   - Header with the title "Clinical Performance Dashboard."
   - Subheaders for selecting filters based on "Month" and "Department."

2. **Data Visualization**
   - A structured layout that displays the performance of different departments in the hospital based on various Key Performance Indicators (KPIs).

### Table Visualization Requirements

In this section, we outline the requirements for the Table Visualization in the Clinical Performance Dashboard. The Table Visualization will display key clinical performance metrics by department, providing a structured and comprehensive view of the data. The table will include the following columns and features:

| Order | Column Name               | Description                                              |
| ----- | ------------------------- | -------------------------------------------------------- |
| 1     | Clinical Measure Name     | Name of the clinical measure being evaluated.            |
| 2     | Current Month Metric Rate | The rate of the metric for the current month.            |
| 3     | Trend Indicator           | A green arrow for improvement, or a red arrow for decline in the metric rate. |
| 4     | Metric Rate Calculation    | Calculated as Metric Rate Numerator Value / Metric Rate Denominator Value. Denominator is Total Patients. |
| 5     | Points Earned             | Points earned for each metric rate.                     |
| 6     | 13-Month Trend            | A sparkline chart showing the last 13 months' metric rate trend. |

### Back-end Data Structure

The dashboard will be powered by a monthly summary table with columns such as Period Month, Department ID, Department Name, Metric ID, Metric Name, Metric Numerator Value, Metric Denominator Value, and Points Earned.

### Collaboration and Contribution

This project aims to demonstrate Looker's ability to transform raw healthcare data into actionable insights, providing healthcare professionals with a powerful tool for data-driven decision-making.

**Let's Get Started!**

This project is not just a solo endeavor; it's an invitation for collaboration. We'll be working on this Looker Proof of Concept (POC) together, and your input and insights are highly valued. Whether you're a seasoned data analyst or just getting started, everyone is welcome to contribute.

Stay tuned for the implementation steps and solutions that will be shared as we progress. Let's harness the power of Looker to transform healthcare analytics and improve patient outcomes.
