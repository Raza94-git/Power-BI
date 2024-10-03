# Power BI Insurance Project
This project showcases the complete development process of an insurance report using Power BI. It covers everything from loading data into SQL Server, cleaning and transforming data in Power BI, creating advanced visualizations, and publishing reports to Power BI Services.

## Key Steps:

**Data Loading:**

The project begins by creating a database in SQL Server Management Studio (SSMS) and loading a flat file into the creatd database.
The data is then imported into Power BI for further analysis.

**Data Profiling & Cleaning:**

Using the Power Query Editor, data types, distinct values, and null values were checked.
Duplicate rows were identified and removed.

**Visualization:**

Slicers were added for filtering by customer ID, policy number, and claim number.
Cards were created for numerical columns like premium, claim, and coverage amounts.
Various charts, including bar charts, line charts, and donut charts, were implemented to represent key metrics such as policy status, claim amount by age group, and claim status by policy type.

**Advanced Reporting:**

Drill-through functionality was added, enabling deeper insights into specific policy types and claim statuses.
A second report page was created for detailed analysis and interactivity.

**Publishing & Scheduling Refreshes:**

The report was published to Power BI Services, allowing it to be shared with team members.
A daily refresh schedule was set up to ensure the report remains dynamic, reflecting any updates in the SQL Server data.

**Creating Roles:**

Roles were created to manage access control, allowing managers to view data relevant to their specific policy types (e.g., travel insurance, health insurance).
These roles were tested and managed within Power BI Services.

**Dashboard Creation:**

A dashboard was created within the Power BI services by pinning the most important KPIs and visuals from the report, allowing quick access to the most critical metrics.
The dashboard can also be shared with team members, with appropriate permissions granted.

**Sentiment Analysis:**

The project also features a sentiment analysis of customer feedback using Power BI’s AI tools.
A word cloud was created to visualize common feedback terms, and a bar chart categorized feedback into “Excellent,” “Good,” and “Needs Improvement” groups.
