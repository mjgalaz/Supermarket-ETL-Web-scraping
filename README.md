# Supermarket Data Analysis Project, Web Scraping Competitors table from Wikipedia and ETL

This project aims to understand the ETL process, focusing on web scraping to obtain complementary data and designing a data schema with fact and dimension tables. By defining these tables, we gather inputs for analyzing Superstore and its competitors' data.

### Project Workflow
1. Extraction
- Extract data from the Superstore table and perform web scraping using Python in Google Colab to retrieve the "List of supermarket chains" table from Wikipedia, containing competitor data by country.
2. Transformation
Key tasks during this phase include:

- Cleaning and sorting Wikipedia table data by country.
- Standardizing country names for data integration.
- Design the database structure (Snowflake Schema in this case).
3. Loading
- Load the Superstore and multinational_final tables (cleaned and reorganized Wikipedia table).
4. Exploratory Data Analysis and Dashboard Creation
- Conducting exploratory data analysis to understand data distributions and relationships.
- Creating visualizations using Power BI to present key findings.
- Developing interactive dashboards to provide stakeholders with a comprehensive view of the data.


### Tools, Languages, and Inputs
1. Tools and Platforms
-  Google BigQuery: for creating table structures.
- Python in Google Colab: for web scraping and data extraction.
- Power BI: for exploratory data analysis and dashboard creation.
2. Languages
- SQL: for querying in Google BigQuery.
- Python: for web scraping and data manipulation in Google Colab.

### Snowflake Schema Design - Definition of Fact and Dimension Tables
![](https://raw.githubusercontent.com/mjgalaz/Supermarket-ETL-Web-scraping/main/Snowflake%20Schema%20Design.png)


### Dashboard
![](https://raw.githubusercontent.com/mjgalaz/Supermarket-ETL-Web-scraping/main/dashboard.png)
