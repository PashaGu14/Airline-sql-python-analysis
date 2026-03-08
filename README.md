
# Airline Operations & Performance Analysis
1. Executive summary
2. Overview / problem
3. Tech stack
4. Dataset
5. Workflow
6. Results & analysis (with charts)
7. Key insights
8. Skills demonstrated
9. Repo structure
10. Conclusion
11. How to run

---

**SQL · Python · Relational Database Analytics · Operational Performance Insights**

This project was built to analyzes operational performance in the U.S. airline industry using a relational database of flight records. The objective is to evaluate airline reliability, flight volume trends, and delay performance using SQL-based data querying and Python-based visualization.

The workflow combines **relational database analysis with Python data visualization** to transform structured operational data into actionable insights.

---

# Executive Summary

I devloped this analysis to examine airline operational performance using a relational dataset of flight records. The study focuses on airline arrival delays, flight activity trends, and total flight volume.

The results show measurable differences in **average arrival delays between airlines**, indicating variability in operational reliability. Monthly flight activity visualizations reveal **seasonal fluctuations in flight volume**, reflecting patterns in travel demand. Flight volume analysis highlights how airline operations scale across carriers.

These findings demonstrate how SQL and Python can be used together to analyze operational datasets and uncover meaningful performance trends.

---

# Overview

Airline operations generate large volumes of structured data across multiple entities including flights, airlines, aircraft, airports, and weather observations. This project explores how these variables interact and evaluates airline performance across several operational dimensions.

The analysis focuses on:

* airline flight volume and operational scale
* on-time performance and delay patterns
* monthly and seasonal activity trends
* comparative performance across airlines
* relationships between weather conditions and flight operations

SQL is used to extract and aggregate data, while Python is used to structure results and generate visual analysis.

---

# Tech Stack

| Tool                    | Role                                     |
| ----------------------- | ---------------------------------------- |
| **Python**              | Data analysis workflow                   |
| **pandas**              | DataFrame creation and query execution   |
| **SQL**                 | Relational data querying and aggregation |
| **SQLite / SQL engine** | Database storage and query processing    |
| **Seaborn**             | Statistical visualization                |
| **Matplotlib**          | Chart rendering                          |
| **Jupyter Notebook**    | Analysis environment                     |

---

# Dataset Structure

The dataset consists of several relational tables:

| Table        | Description                                 |
| ------------ | ------------------------------------------- |
| **flights**  | Flight-level operational records            |
| **airlines** | Airline carrier codes and names             |
| **airports** | Airport location and metadata               |
| **planes**   | Aircraft model and manufacturer information |
| **weather**  | Hourly weather observations                 |

These tables are joined using SQL to analyze airline operations across multiple performance dimensions.

---

# Key Techniques Used

The analysis combines SQL querying and Python visualization.

**Data Querying**

* SQL `JOIN` operations to combine airline data
* `GROUP BY` aggregation to calculate averages and totals
* Filtering of `NULL` values for accurate delay calculations
* Sorted results for clearer comparisons

**Data Visualization**

* Charts created using **Seaborn** and **Matplotlib**
* Visualizations used to highlight airline performance differences and operational trends.

---

# Analytical Workflow

The project follows a structured analysis process:

1. **Data Exploration**

   * Inspect relational tables and validate schema structure.

2. **On-Time Performance Analysis**

   * Identify flights with zero departure and arrival delays.

3. **Airline Flight Volume**

   * Aggregate total flights by airline to measure operational scale.

4. **Monthly Flight Activity**

   * Analyze airline flight counts across months to identify seasonal trends.

5. **Reusable SQL Query Function**

   * Build a Python function to dynamically query airline flight counts by month.

6. **Airline Delay Benchmarking**

   * Calculate mean arrival delays by airline.

7. **Performance Visualization**

   * Create bar charts comparing airline delay performance.

8. **Weather Relationship Exploration**

   * Examine potential relationships between weather conditions and flight operations.

---

# Results and Analysis

## Airline Delay Comparison

<img width="1118" height="360" alt="newplot copy" src="https://github.com/user-attachments/assets/fb61dca3-52ce-4940-8dfa-08a1febe26b2" />

The airline delay comparison chart shows the **average arrival delay by airline**. The results indicate notable differences in delay performance across carriers. Some airlines consistently demonstrate lower average delays, suggesting stronger operational reliability, while others experience higher delay averages that may reflect operational constraints or scheduling pressures.

---

## Monthly Flight Activity Trends

<img width="1118" height="360" alt="newplot" src="https://github.com/user-attachments/assets/2671ac43-f619-425f-a0f4-3f9e3e366780" />

Monthly flight activity visualizations reveal **seasonal patterns in airline operations**. Flight counts increase during peak travel months and decline during lower demand periods. These fluctuations illustrate how airline operations scale to meet seasonal travel demand.

---

## Flight Volume Results

<img width="374" height="240" alt="Screenshot 2026-03-07 at 12 15 32 PM" src="https://github.com/user-attachments/assets/9c0be443-56eb-4075-9372-0ad4c3b727d6" />

Flight volume analysis highlights the **distribution of total flights across airlines**. The results show that a small number of carriers account for a significant portion of total flight activity, demonstrating differences in operational scale across the industry.

---

# Key Insights

Key observations from the analysis include:

* Airline performance varies significantly when measured by **average arrival delay**.
* A small subset of airlines operates a **large proportion of total flights**.
* Monthly flight counts reveal **clear seasonal demand patterns**.
* Weather variables can be integrated with flight data to support deeper operational analysis.

---

# Skills Demonstrated

This project demonstrates several practical analytics skills:

* SQL querying and relational database analysis
* Multi-table joins and aggregation logic
* Programmatic SQL execution using Python
* Reusable analytical functions
* Operational performance benchmarking
* Seasonal trend analysis
* Data visualization for comparative analysis

---

# Repository Structure

```
airline-performance-analysis
│
├── airline_analysis.ipynb
├── README.md
├── data/
│   └── airline_database_files
└── visualizations/
```

---

# Conclusion

This analysis demonstrates how relational databases and Python analytics tools can be combined to evaluate airline operational performance. Differences in average airline delays highlight variability in reliability, while seasonal patterns in flight activity illustrate changes in travel demand. These findings provide a foundation for deeper operational analysis and performance benchmarking within the airline industry.

---

# How to Run

Clone the repository and install dependencies:

```bash
git clone <repo-url>
cd airline-performance-analysis
pip install pandas seaborn jupyter
jupyter notebook
```

Open the notebook and run the analysis cells sequentially.

---

**Portfolio Note**

This project was developed to demonstrate practical skills in **SQL-based relational data analysis, Python data processing, and operational performance visualization.**


