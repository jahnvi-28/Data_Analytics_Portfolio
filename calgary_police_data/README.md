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

- **Mapped Calgary communities using GeoData (MultiPolygon) and `folium`**
- **Visualized crime counts by community on an interactive choropleth map**
- **Performed temporal analysis** to compare average crimes on:
  - Public holidays
  - Weekends
  - Weekdays
- **Calculated daily average crime rates** for each day type
- **Built visualizations using `matplotlib`** to communicate findings clearly

## Project Structure

Calgary_Crime_Analysis/
│
├── data/
│ ├── crime_data.csv # Raw crime dataset from Calgary Open Data
│ ├── Community_District_Boundaries.csv # Boundary data with MULTIPOLYGON geometry
│ └── public_holidays.csv # List of public holidays in Alberta
│
├── notebooks/
│ └── Calgary_Crime_2024_Analysis.ipynb # Jupyter notebook with full analysis
│
├── outputs/
│ └── crime_map.html # Exported interactive map (optional)
│
└── README.md # This file

## Tools & Libraries

- **Python (Pandas, NumPy)** for data manipulation
- **Folium** for interactive maps
- **GeoPandas & Shapely** for handling spatial data
- **Matplotlib & Seaborn** for charts
- **Jupyter Notebook** for documenting the analysis

## Sample Insight

> **Crime spikes dramatically on public holidays**, with an average of ~1,860 crimes per day, compared to ~273 on weekdays and ~266 on weekends.

This may indicate a need for more focused policing and awareness during public events and holidays.

## Next Steps

- Deep dive into **crime types** to see what’s driving holiday spikes
- Explore **monthly or seasonal trends**
- Add **time series forecasting or anomaly detection**

## Credits

- **Crime and community boundary data:** [City of Calgary Open Data Portal](https://data.calgary.ca)
- **Public holiday list:** Government of Alberta

Feel free to explore the notebook for detailed code, visualizations, and commentary.
