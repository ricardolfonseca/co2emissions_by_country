# CO2 Emissions by Country Analysis Project

## Overview
This project focuses on analyzing CO2 emissions data from various countries, evaluating emissions in relation to population size and other geographical factors. The objective is to understand and highlight how different countries contribute to global CO2 emissions and how this impacts per capita emissions.

The interactive **Power BI dashboard** is available [here](https://app.powerbi.com/view?r=eyJrIjoiMTVkNzc2NjQtNDE1ZC00NjBjLWEwZTAtMjZhZWE3MWQ2Yzg2IiwidCI6ImFkMjhjNjI1LWYyY2EtNGU5MS1iNmQ2LTE4OTIyYmM5MzkxYyIsImMiOjh9).

## Project Goals
- **Analyze CO2 emissions**: Measure and compare emissions across different countries.
- **Population Density and Emissions**: Explore how population density relates to CO2 emissions per capita.
- **Environmental Impact**: Provide insights into how countries' emissions relate to their population and land area, offering a valuable perspective for environmental efforts.

## Data Sources
The project uses publicly available datasets related to:
- **CO2 Emissions**: Historical emissions data by country.
- **Population**: 2022 population data by country.
- **Geographical Data**: Land area and percentage of global land mass by country.

## Database Design
The project uses a PostgreSQL relational database structured as follows:
- **Fact Table**: `fact_emissions` contains data on CO2 emissions, population, area, and year.
- **Dimension Table**: `dim_country` stores details about each country, such as its population, area, and continent information.
  
### ERD (Entity Relationship Diagram)
The database follows a star schema where `dim_country` is related to `fact_emissions` by `country_id`.

## Additional Information
Please consult the Project Documentation manual in this repository for more information and step by step.
Also check the SQL queries and PBI file.

Thank you,
Ricardo Fonseca
