# Data-Visualization-Final-project
#  Movies Performance Analytics Dashboard

An interactive Power BI dashboard that transforms raw movie industry data into meaningful business insights through data cleaning, feature engineering, and visual analytics.

---

##  Project Overview

This project was developed to analyze global movie performance and help identify the genres, directors, actors, and financial patterns associated with commercial and critical success. The dashboard enables users to explore movie performance across multiple dimensions using interactive visualizations and dynamic filters.

The project follows the complete Business Intelligence workflow:

* Data Cleaning & Preprocessing (ETL)
* Data Modeling
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Interactive Dashboard Development in Power BI

---

##  Dataset

The original dataset consisted of **6 relational tables** containing movie metadata, ratings, genres, cast, crew, and financial information. These tables were transformed into a single analytical dataset optimized for reporting.

### Source Tables

* Movies
* Ratings
* Genres
* Names
* Director Mapping
* Role Mapping

### Final Analytical Dataset

* **4,919 Movies**
* **25 Analytical Columns**

---

##  Data Preparation

The following transformations were performed before dashboard development:

* Merged six relational tables into a single analytical table
* Removed inconsistencies and standardized categorical values
* Handled missing values using appropriate techniques
* Created financial metrics such as:

  * Net Profit
  * Return on Investment (ROI)
* Engineered analytical features including:

  * Rating Tier
  * Popularity Flag
  * Decade
  * Financial Data Availability

---

##  Dashboard Features

### Financial & Trend Analysis

* Total Box Office Revenue
* Net Profit
* Average IMDb Rating
* Blockbuster Count
* Revenue vs Rating by Genre
* Risk vs Reward Analysis (Budget vs Box Office)
* Movie Release Trends by Decade

### Ratings & Talent Analysis

* IMDb Rating Distribution
* Rating Tier Breakdown
* Top Directors Leaderboard
* Acclaimed Movies Matrix
* Audience Popularity Analysis

### Interactive Filters

* Genre
* Decade
* Content Rating
* Popularity
* Financial Data Availability

---

##  Key Business Insights

* Action movies generated the highest overall box office revenue.
* Animation and Adventure delivered the highest average revenue per movie.
* Nearly **77%** of movies contained complete financial information for analysis.
* Movies produced with budgets below **$20M** achieved the strongest median ROI.
* Around **6.5%** of movies qualified as "Masterpiece" (IMDb Rating ≥ 8.0).
* More than **70%** of blockbuster movies were released after 2000.

---

##  Tools & Technologies

* Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Modeling
* ETL
* Business Intelligence

---

##  Repository Structure

``text
Movies-Performance-Analytics/
│
├── Dashboard.pbix
├── Dataset/
├── Images/
├── Executive Summary.pdf
├── README.md
└── Demo.mp4
```

---

##  How to Use

1. Clone this repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Refresh the dataset if required.
4. Explore the dashboard using the available slicers and filters.

---

##  Dashboard Preview

> Add dashboard screenshots here.

---

##  Documentation

This repository also includes an Executive Summary explaining:

* Data preparation process
* Dashboard walkthrough
* Analytical findings
* Business recommendations

---

##  Team

This project was completed collaboratively as part of a Business Intelligence project. Special thanks to all teammates and mentors for their guidance, discussions, and support throughout the development process.

---

##  Feedback

Suggestions and feedback are always welcome. Feel free to open an issue or connect with me to discuss improvements and ideas.
