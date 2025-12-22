# Development Indicators Metadata Analysis

## Project Overview
This project analyzes a dataset of development indicators to understand the **thematic composition**, **metadata quality**, and **documentation coverage** of indicators.  
The analysis focuses on identifying dominant topics, evaluating the completeness of metadata fields (methodology, limitations, development relevance), and visualizing the findings using charts such as bar charts, Pareto charts, and donut charts.

The project was completed as part of my **Master’s program** in [Data Science].

---

## Key Objectives
- Explore the dataset and assess overall data quality.
- Analyze the distribution of indicators across **main development topics**.
- Evaluate metadata coverage for critical fields.
- Provide insights on **topic concentration** and **documentation gaps**.
- Create visualizations to support interpretation and reporting.

---

## Methodology
1. **Data Preparation**
   - Standardized the `Topic` column to extract **Main Topic** categories.
   - Handled missing values in key metadata fields.
   
2. **Exploratory Data Analysis (EDA)**
   - Assessed non-null counts and data types.
   - Identified the top sources and topics of indicators.
   
3. **Metadata Coverage Analysis**
   - Created presence flags for:
     - `Statistical concept and methodology`
     - `Limitations and exceptions`
     - `Development relevance`
   - Calculated percentage coverage per topic.
   
4. **Visualization**
   - **Grouped bar charts** for metadata coverage.
   - **Pareto charts** to show topic concentration.
   - **Donut charts** to illustrate top topic distribution.

---

## Key Findings
- A **small number of topics dominate** the dataset (Pareto principle observed).
- Metadata coverage varies across topics; **development relevance** is better documented than methodology or limitations.
- Several topics show gaps in metadata, highlighting opportunities for **documentation improvement**.
- The dataset is **unevenly distributed**, with certain topics heavily represented while others are sparse.

---

## Visualizations
- **Metadata Coverage by Topic** (Grouped Bar Chart)  
- **Pareto Chart of Main Topics**  
- **Donut Chart of Top 7 Main Topics**  

*(See `notebooks` or `figures` folder for all charts.)*

---

## Dataset
The dataset used is publicly available on Kaggle:  
[Kaggle Dataset – Development Indicators Metadata](https://www.kaggle.com/datasets/vijayveersingh/world-banks-global-indicator-data)

---

## Code
All code for preprocessing, analysis, and visualization is available on GitHub:  
[GitHub Repository]([https://github.com/your-username/masters-projects](https://github.com/soroush-jhnn/master_projects/blob/main/Data_visualization/matplot.ipynb))

---
