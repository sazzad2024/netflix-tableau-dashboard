# 🎬 Netflix Global Content Analysis

**An interactive Tableau dashboard analyzing trends in Netflix's content strategy, global distribution, and rating demographics.**

## 📊 Project Overview
This project visualizes a dataset of over 8,000 Netflix titles to uncover insights about the platform's content strategy. The dashboard allows users to filter by **Content Type (Movie vs. TV Show)** to dynamically explore how Netflix caters to different global audiences and age groups.

## 🔍 Key Visualizations
* **Global Content Footprint:** A geospatial heat map visualizing content volume by country, highlighting production hubs like the USA, India, and the UK.
* **Audience Demographics:** A Tree Map analyzing the target audience, distinguishing between mature (TV-MA, R) and younger demographics.
* **Top Genres:** A horizontal bar chart ranking the most popular categories to identify dominant content themes.
* **Duration Statistics:** A Box-and-Whisker plot revealing the statistical spread of movie lengths across different maturity ratings (analyzing medians and outliers).
* **Content Trends:** A time-series analysis showing the exponential growth of content added to the platform over the last decade.

## 🛠️ Tools & Techniques Used
* **Tableau Public:** Data visualization and dashboard design.
* **Data Modeling:** Implemented a **Star Schema** relationship model (joining `Titles`, `Countries`, and `Genres`) to handle one-to-many relationships without data duplication.
* **Data Cleaning:** Applied Data Source Filters to remove corrupted records (e.g., mismatched data types) and handle Null values.
* **Statistical Analysis:** Used Box Plots to determine quartiles and outliers in movie duration.
* **Interactive Design:** Created global filters and "Apply to All" logic to ensure a seamless user experience.

## 📈 Key Insights
* **Production Hubs:** While the US is the primary producer, India shows a massive volume of content relative to other international markets.
* **Maturity Level:** The majority of Netflix's library is rated **TV-MA** or **TV-14**, indicating a strategy focused heavily on adult and teen audiences rather than children.
* **Duration Consistency:** Adult-rated movies (R, PG-13) show a consistent median duration of ~95-100 minutes, whereas children's content varies significantly.

**Author:** A K M Sazzadul Alam  
**Data Source:** Netflix Movies and TV Shows Dataset
