# Tech Job Market & Developer Trends Analysis (2024)

## About This Project
This project explores the 2024 Stack Overflow Developer Survey alongside tech job market data using API calls and web scraping to understand trends in developer demographics, compensation, and in-demand skills.

Note: This project was created as part of the IBM Data Analyst Certificate Capstone on Coursera. While certain datasets and guidance were provided, all analysis, data wrangling, insights, and visualizations are my own work.

The project allowed me to apply the full data analysis workflow—cleaning and wrangling raw survey data, conducting exploratory analysis, detecting and handling outliers, and generating meaningful insights through visual and statistical methods.

## Project Overview
This repository is split into two major parts:

### 1. Job Market Research (API & Web Scraping)
- Objective: Understand which technical skills are in demand and what the average salaries look like across different technologies.
- Sources:
  - Job postings dataset from PromptCloud via Kaggle
   - Web-scraped salary data from publicly available websites (e.g., PayScale, Indeed)
- Tasks Performed:
   - Used the requests library to fetch job posting data via API
   - Parsed and extracted relevant salary information using BeautifulSoup
   - Cleaned and visualized skill and salary data to uncover top skills and compensation trends

### 2. Stack Overflow Developer Survey Analysis (2024)
- Objective: Explore the global developer landscape by analyzing the annual Stack Overflow survey.
- Dataset: 2024 Stack Overflow Developer Survey (CSV)
- Tasks Performed:
  - Data Wrangling:
  - Cleaned missing and inconsistent values
  - Handled nulls and duplicate records
  - Detected and removed outliers (especially in compensation data) using IQR method
- Exploratory Data Analysis:
  - Uncovered patterns in developer roles, employment types, education levels, learning methods, language usage, and compensation
  - Binned salary data and performed grouped aggregations (e.g., median and IQR by role, age, education)
  - Visualized trends using bar plots, boxplots, histograms, and word clouds
- Dashboard:
  - Created an interactive dashboard in Google Looker Studio to summarize key insights

## Technologies Used
Languages
- Python 3.x

Libraries
- Data Handling: ```pandas```, ```numpy```, ```collections.Counter```
- Visualization: ```matplotlib```, ```seaborn```, wordcloud```
- Web Scraping & APIs: ```requests```, ```BeautifulSoup```

Tools:
- Google Looker Studio (Dashboard)
- PowerPoint or Google Slides (Presentation)

## Files in This Repository
- api_webscraping_analysis.ipynb: API and web scraping analysis notebook
- stack_overflow_analysis.ipynb: Full EDA on the Stack Overflow 2024 data
- lookers_dashboard.pdf: Screenshot or link to the Looker dashboard
- final_presentation.pdf: Summary of key insights (content created by me)
- README.md:	This documentation

## Key Insights
Some of the insights uncovered include:
- Python, JavaScript, and SQL remain the most in-demand languages in job postings.
- Most developers are between 18–44 years old and have at least a bachelor’s degree.
- Developers learning via online communities, blogs, and certifications are dominating.
- Median compensation varies widely by developer role and tends to increase with age and seniority.

## Attribution & Notes
This project was guided by the Capstone module of the [IBM Data Analyst Certificate on Coursera](https://www.coursera.org/professional-certificates/ibm-data-analyst).

All data analysis, visualization, and insights were generated independently.
