# Data Analyst Job Market Analysis

## Project Overview

This project analyzes Data Analyst job postings to understand demand for skills, salary patterns, locations, seniority levels, remote opportunities, and entry-level positions.

The analysis uses job posting data from Luke Barousse's Data Analyst job dataset and focuses on identifying patterns that can help entry-level candidates better understand the Data Analyst job market.

## Dataset

* **Source:** Luke Barousse's Data Analyst job dataset
* **Job postings analyzed:** 38,570
* **Date range:** November 4, 2022 – April 18, 2025
* **Postings with standardized salary information:** 5,974
* **Median reported salary:** $83,440

### Data Limitations

Salary information was available for only 15.5% of the Data Analyst postings. Therefore, salary findings are based only on postings with reported salary information.

The dataset ends on April 18, 2025, so 2025 represents a partial year and should not be compared directly with complete calendar years.

### Data Availability

The original dataset files are not included in this repository because they exceed GitHub's file-size limit. The analysis was performed locally using Luke Barousse's Data Analyst job dataset.

## Key Questions

* What skills are most frequently requested in Data Analyst job postings?
* How does salary vary by skill and career level?
* Where are Data Analyst jobs concentrated?
* How common are remote opportunities?
* How large is the entry-level Data Analyst job market?
* What skills are most commonly requested in entry-level Data Analyst postings?

## Tools & Technologies

* **Python** — data cleaning, analysis, and visualization
* **Pandas** — data manipulation and analysis
* **Matplotlib** — data visualization
* **SQL** — querying and analyzing job market data
* **Tableau** — interactive data visualization
* **Jupyter Notebook** — analysis workflow and documentation

## Key Findings

* **SQL** was the most frequently requested skill, appearing in more than half of Data Analyst job postings.
* **Excel, Power BI, Python, and Tableau** were also among the most frequently requested skills.
* **SQL and Tableau** had the highest median reported salary among the selected skills at **$96,500**.
* Approximately **39.0%** of Data Analyst postings explicitly indicated remote work.
* Only **2.6%** of all postings were explicitly classified as **Junior / Entry** level.
* Among explicitly entry-level postings, **Excel, SQL, Tableau, and Power BI** were the most commonly requested skills.
* Approximately **61.2%** of explicitly entry-level postings indicated remote work.

'''
## Project Structure

project_1_job_market/
│
├── charts/       # Analysis charts
├── data/         # Local dataset files (not included on GitHub)
├── notebooks/    # Jupyter notebooks
├── powerbi/      # Power BI visualizations
├── sql/          # SQL analysis
├── tableau/      # Tableau visualizations
└── README.md     # Project documentation
'''

## Analysis

The project examines the Data Analyst job market through several areas:

* **Skills in Demand** — identifies the most frequently requested skills.
* **Skill Trends** — examines how skill demand changed over time.
* **Salary Analysis** — compares reported salaries across skills and career levels.
* **Location Analysis** — examines job concentration by city and remote-work status.
* **Seniority Analysis** — examines the distribution of job postings across career levels.
* **Job Market Overview** — analyzes job posting volume over time.
* **Entry-Level Opportunities** — examines entry-level job volume, skills, remote opportunities, and reported salaries.

## Conclusion

This project provides a data-driven overview of the Data Analyst job market, with a particular focus on skills and opportunities relevant to entry-level candidates.

The findings should be interpreted as patterns within this dataset rather than a complete representation of the entire Data Analyst job market.


