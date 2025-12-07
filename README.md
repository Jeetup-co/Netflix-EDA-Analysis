📊 Netflix Movies & TV Shows — Exploratory Data Analysis (EDA)

A complete exploratory analysis of Netflix’s content library to uncover insights into content distribution, trends, and platform strategy.

📁 Project Overview

This project performs an in-depth exploratory data analysis (EDA) on the Netflix Titles Dataset, which contains information about movies and TV shows available on Netflix.
The goal is to identify:

🎬 Distribution of Movies vs TV Shows

🌍 Countries producing the most Netflix content

📅 Content addition trends over the years

🏷️ Top genres/categories

👨‍💼 Directors & actors dominating Netflix

🔞 Ratings distribution

🧼 Data cleaning decisions

🔍 Overall insights & conclusions

This project is portfolio-ready and demonstrates strong skills in:

Python

Pandas

NumPy

Data Cleaning

Data Visualization (Matplotlib/Seaborn)

Storytelling With Data

📚 Dataset Description

The dataset contains the following key columns:

Column	Description
show_id	Unique ID for each title
type	Movie / TV Show
title	Name of the content
director	Director(s) of the content
cast	Actors featured
country	Country of origin
date_added	Date it was added to Netflix
release_year	Year the content was released
rating	Content rating (TV-MA, PG-13, etc.)
duration	Duration (Movies → minutes, TV Shows → seasons)
listed_in	Genre/category
description	Brief summary
🧽 Data Cleaning Summary

To prepare the data for analysis:

✔ Handled missing values (director, cast, country)
✔ Cleaned date_added & converted to datetime
✔ Corrected inconsistent formatting
✔ Splitted multi-valued fields (country, genre)
✔ Standardized column names
✔ Extracted new columns (e.g., year_added)

📈 Key Analyses Performed
1️⃣ Movie vs TV Show Distribution

Count visualization of Movies vs TV Shows

Insights on Netflix's content strategy

2️⃣ Country-Wise Content Distribution

Identifying top countries producing Netflix content

Understanding geographic content dominance

World map / bar chart visualizations

3️⃣ Yearly Trend — Content Added Over Time

Number of titles added each year

Trend before and after 2015

Growth pattern of Netflix’s library

4️⃣ Rating Distribution

Most common content ratings

Comparison between Movies and TV Shows ratings

5️⃣ Genre / Category Analysis

Most popular genres

Genre frequency visualization

Genre dominance by country

6️⃣ Directors and Cast Analysis

Directors with maximum titles on Netflix

Actors with most appearances

📘 Insights & Findings 
🔥 1. Netflix has more Movies than TV Shows

Movies dominate the platform, indicating Netflix’s strategy to prioritize films over series.

🌍 2. The US, India, and UK produce the most Netflix content

These three countries contribute the highest number of titles, showing strong regional partnerships and production power.

📅 3. Netflix’s content library grew rapidly after 2015

There was a huge spike in content additions between 2016–2020, aligning with Netflix's global expansion.

🔞 4. Most content is rated TV-MA

This indicates Netflix's focus on mature audiences compared to family/kids segments.

🎭 5. The most frequent genres are:

Dramas

Comedies

International Movies

Documentaries

This suggests that Netflix caters heavily to global and diverse audiences.

🎬 6. Top directors & actors appear repeatedly

Certain directors and actors dominate Netflix content, showing recurring collaborations.

📝 Conclusion

This EDA reveals that:

Netflix is heavily focused on movies, especially TV-MA–rated content.

The platform expanded significantly after 2015, increasing its global footprint.

US, India, and UK dominate content production.

Drama, Comedy, and International genres are most common.

The dataset shows clear trends that reflect Netflix’s global growth strategy and content diversification.

This project demonstrates strong data cleaning, visualization, and insight extraction, making it suitable for professional portfolios and GitHub.

🧑‍💻 Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Google colab
