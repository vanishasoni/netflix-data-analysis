# ?? Netflix Data Analysis Dashboard

An interactive data visualization project analyzing the Netflix content catalog using Tableau and Python.

![Netflix Dashboard](Images/dashboard_screenshot.png)

---

## ?? Project Overview

This project explores the trends in Netflix's library including content growth over time, genre distribution, country-wise contributions, and more. It is ideal for practicing data cleaning, exploratory data analysis (EDA), and Tableau dashboarding.

---

## ?? Dataset

- **Source:** [Kaggle - Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Total Records:** ~8,800
- **Fields Used:** Title, Type, Country, Date Added, Rating, Duration, Genre, etc.

---

## ?? Dashboard Features

?? Titles Added Per Year  
?? Movie vs TV Show Distribution  
?? Top 10 Countries by Content Volume  
?? Most Popular Genres  
?? Average Movie Duration Over the Years  
?? Rating Distribution

---

## ?? Tools & Technologies

| Tool       | Purpose                       |
|------------|-------------------------------|
| **Python** | Data cleaning & preprocessing |
| **Pandas** | Date formatting, text parsing |
| **Tableau**| Interactive dashboard         |

---

## ?? Live Tableau Dashboard

?? [Click here to view the interactive dashboard] https://public.tableau.com/views/ProjectNetflix_17517342465430/Sheet5?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## ?? Data Cleaning Highlights

- Converted `date_added` to datetime format
- Extracted `year_added` and `month_added`
- Split `duration` into `duration_int` and `duration_type`
- Filled null values in key fields (`country`, `rating`, `genre`, etc.)

---

## ?? Folder Structure

