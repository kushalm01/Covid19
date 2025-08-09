Global COVID-19 Data Analysis
This project performs an end-to-end analysis of historical COVID-19 data to uncover global trends, identify the most affected countries, and visualize the pandemic's impact. It demonstrates a complete data analysis workflow, from data acquisition and cleaning to visualization and insights generation.

Technologies Used 🛠️
Python: For data fetching, cleaning, and initial exploration using pandas and matplotlib.

SQL (SQLite): For structuring the cleaned data into a relational database and performing data aggregation.

Power BI: For creating an interactive and professional dashboard to visualize key findings.

Data Source 📊
The dataset used for this project is the Weekly COVID-19 Cases data, sourced from Our World in Data, a project of the University of Oxford.

Project Workflow ⚙️
The project followed a structured data analysis pipeline:

Data Acquisition & Cleaning:

The raw data was fetched directly from the Our World in Data API using Python's pandas library.

The Day column was converted to a proper datetime format for time-series analysis.

Data was meticulously cleaned by filtering out regional and economic groupings (e.g., 'World', 'Europe') to ensure the analysis focused only on individual countries.

Data Storage & Querying:

The cleaned data was loaded into a local SQLite database file, demonstrating proficiency in database management.

SQL queries were written to perform aggregations, such as calculating the total cases per country, to prepare the data for visualization.

Data Visualization & Insights:

The final dashboard was built using Power BI by connecting to the local SQL database.

The dashboard presents key insights through an interactive interface, including time-series trends and geographical distribution of cases.

Key Insights from the Analysis 🔍
Total Cases by Country: A ranking of countries by their total number of confirmed cases.

Time-Series Trends: A visualization of the progression of weekly cases over the entire pandemic timeline for selected countries.

Geographical Impact: A map-based representation showing the distribution of cases worldwide.
