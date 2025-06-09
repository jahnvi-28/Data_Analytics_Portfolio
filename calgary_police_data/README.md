# Calgary Police Data - Crime & Disorder Statistics Analysis
This project analyzes crime patterns across Calgary communities using open data from the City of Calgary. The analysis includes spatial mapping, time-based trends, and insights into how crime rates vary across weekdays, weekends, and public holidays.

## Project Objective

To explore and visualize crime trends in Calgary using 2024 data. The goal is to uncover actionable insights and demonstrate skills in:

- Data wrangling and cleaning
- Exploratory data analysis (EDA)
- Geographic data visualization using Python
- Working with public datasets
- Drawing insights from temporal trends

## Key Highlights

- **Mapped Calgary communities using GeoJson data and `folium`**
- **Visualized crime counts by community on an interactive choropleth map**
- **Performed temporal analysis** to compare average crimes on:
  - Public holidays
  - Weekends
  - Weekdays
- **Calculated daily average crime rates** for each day type
- **Built visualizations using `matplotlib`** to communicate findings clearly

## Project Structure

Calgary_Crime_Analysis/
Data:
- crime_data.csv: Raw crime dataset from Calgary Open Data
- Community_District_Boundaries.csv: Boundary data in GeoJSON format
- public_holidays.csv: List of public holidays in Alberta

Notebooks:
- Calgary_Crime_2024_Analysis.ipynb: Jupyter notebook with full analysis

Outputs:
- Interactive Map - [Open Interactive Calgary Crime Map](CalgaryMap.html)

README.md: This file

## Tools & Libraries

- **Python (Pandas, NumPy)** for data manipulation
- **Folium** for interactive maps
- **Matplotlib & Seaborn** for charts
- **Jupyter Notebook** for documenting the analysis

**Key Insights:**  
- Crime peaks in summer and dips in winter.  
- Vehicle-related theft is the most common crime.  
- Beltline and Downtown areas have the highest crime rates.  
- Crime dropped significantly during COVID-19 lockdowns.

[View full analysis notebook](calgary_crime_analysis.ipynb)

## Credits

- **Crime and community boundary data:** [City of Calgary Open Data Portal](https://data.calgary.ca)
- **Public holiday list:** Government of Alberta