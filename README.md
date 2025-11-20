# Japan_Socio_Economic_Atlas
A portfolio project using Python/SQL to model Japanese census and economic data. Demonstrates relational data integration, advanced SQL querying (GROUP BY/JOINs), and Power BI visualization for socio-economic analysis.
# Project 2: Socio-Economic Atlas of Japan's Prefectures

## 1. Project Objective
The goal of this project was to model and integrate separate datasets using **SQL** to understand the relationship between population dynamics and economic structure across Japan’s prefectures.

## 2. Core Tools & Skills
* **SQL (SQLite):** Used for relational database modeling, table creation, and performing JOIN queries.
* **Python (Pandas):** Used to load raw CSV data into the SQLite database.
* **Power BI:** Used for the final geospatial visualization and dashboard design.

## 3. The Process (The Relational Model)
1.  **Data Sourcing:** Acquired two separate CSV files: Demographics (Population/Age) and Employment (Economy).
2.  **Database Construction:** Wrote a Python script to build the `japan_atlas.db` file and load the data into two separate, linked tables.
3.  **Data Integration:** Wrote a core **SQL JOIN query** to merge the population data with the economic data based on the 'Prefecture' key.
4.  **Visualization:** Built an interactive Power BI map visual to display key findings by Prefecture.

## 4. Key Findings (The Story)
Finding 1 (Population): The analysis of census data revealed that population is highly concentrated in major metropolitan areas, with Tokyo Metropolis, Osaka Prefecture, and Kanagawa Prefecture being the most populous regions.* Finding 2 (Geospatial): The map visual confirmed that population density is heavily concentrated in the Kanto and Kansai regions. The size of the population bubbles directly correlates with the total population sum, visually emphasizing the stark urban/rural divide.

## 5. Next Steps
The next step will be to search for a clean dataset with a common key to successfully perform the **full SQL JOIN** between demographics and industry data.
