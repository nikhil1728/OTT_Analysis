# 🎬 Netflix OTT Data Analysis | Exploratory Data Analysis & Visualization

## 📌 Project Overview
This project performs an in-depth **exploratory data analysis (EDA)** on Netflix’s content catalog to uncover meaningful insights that can help streaming platforms make **data-driven business decisions**.  
The analysis explores content trends across **movies and TV shows**, geographical markets, genres, release timelines, and contributor patterns (actors/directors).

🔗 **Google Colab Notebook:**  
https://colab.research.google.com/github/nikhil1728/OTT_Analysis/blob/main/OTT_Analysis.ipynb

---

## 👤 Author
**Nikhil Somisetty**  
📅 **Date:** March 18, 2025

---

## 🎯 Business Objective
- Understand Netflix’s content distribution across formats and regions  
- Compare Movies vs TV Shows production trends  
- Identify high-performing genres and countries  
- Determine optimal time windows for content release  
- Support strategic planning using data-backed insights

---

## 🗂 Dataset Description
The dataset contains metadata of **all movies and TV shows available on Netflix as of mid-2021**, consisting of **8,807 titles** and **12 attributes**.

### 📘 Dataset Attributes
| Column Name | Description |
|------------|-------------|
| `show_id` | Unique identifier for each movie or TV show |
| `type` | Content type – Movie or TV Show |
| `title` | Title of the movie or TV show |
| `director` | Director(s) of the content |
| `cast` | Actors appearing in the content |
| `country` | Country or countries where the content was produced |
| `date_added` | Date when the content was added to Netflix |
| `release_year` | Original release year |
| `rating` | Content maturity rating |
| `duration` | Runtime in minutes (movies) or number of seasons (TV shows) |
| `listed_in` | Genre(s) associated with the content |
| `description` | Brief summary of the content |

### 📊 Dataset Summary
- **Total Titles:** 8,807  
- **Movies:** 6,131  
- **TV Shows:** 2,676  
- **Time Span:** 1925 – 2021  

---

## 🔧 Data Cleaning & Preparation
- Performed dataset shape and data type validation
- Handled missing values in:
  - Director
  - Cast
  - Country
  - Rating
- Replaced null categorical values with meaningful labels (e.g., *"Unknown Director"*)
- Converted date fields for time-based analysis
- Ensured zero null values post-processing

---

## 🔄 Feature Engineering (Unnesting)
Multi-valued columns were unnested to enable granular analysis:

- **Genres (`listed_in`)** → Genre-wise trends  
- **Country** → Regional content distribution  
- **Cast** → Actor-level participation  
- **Director** → Director contribution analysis  

This transformation significantly expanded the dataset and enabled accurate bivariate and categorical analysis.

---

## 📊 Key Insights
- 🎥 Movies dominate overall Netflix content, but **TV Shows show strong growth in recent years**
- 🌍 **USA and India** are the top content-producing countries
- **Japan and South Korea** show **higher dominance in TV Shows than Movies**
- 🎭 **International Movies, Dramas, and Comedies** are the most produced genres
- 🗓 **Friday** is the most common and effective release day
- 🎄 **December** emerges as the most favorable release month
- ⏳ Most titles are added to Netflix **within 1–2 years of their original release**

---

## 💡 Business Recommendations
- Increase focus on **TV Shows**, especially in Asian markets
- Strengthen investment in **International and Drama-based content**
- Schedule major content drops on **Fridays**
- Target **holiday seasons (December)** for high-impact releases
- Prioritize acquiring **recently released content** to maintain relevance
- Leverage frequently appearing actors and directors for audience retention

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## ✅ Project Outcome
This project demonstrates how structured EDA can convert raw OTT data into **actionable insights**, enabling better decisions around **content production, regional expansion, and release strategy**.

