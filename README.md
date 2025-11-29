# 🎬 Netflix OTT Data Analysis | EDA & Visualization

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on Netflix’s content catalog to uncover trends that help in **content strategy and business decision-making**.  
The analysis focuses on Movies vs TV Shows, country-wise distribution, genres, actors/directors, and optimal content release timing.

🔗 **Google Colab Notebook:**  
https://colab.research.google.com/github/nikhil1728/OTT_Analysis/blob/main/OTT_Analysis.ipynb

---

## 🎯 Business Objective
- Identify what type of content Netflix should focus on
- Compare Movies vs TV Shows across countries and time
- Understand popular genres, actors, and directors
- Find the best time to release content on OTT platforms

---

## 🗂 Dataset Summary
- **Total Titles:** 8,807  
- **Movies:** 6,131  
- **TV Shows:** 2,676  

**Key features:**  
`Type, Country, Release Year, Date Added, Rating, Duration, Genre, Cast, Director`

---

## 🔧 Data Processing
- Handled missing values using meaningful placeholders
- Converted date fields for time-based analysis
- Unnested multi-valued columns:
  - Genre (`listed_in`)
  - Country
  - Cast
  - Director  
- Created separate datasets for granular analysis

---

## 📊 Key Insights
- 🎥 Movies dominate overall, but **TV Shows are growing rapidly**
- 🌍 **USA and India** produce the most content
- 🇯🇵 🇰🇷 Japan & South Korea have stronger **TV Show dominance**
- 🎭 **International Movies, Dramas, and Comedies** are top-performing genres
- 🗓 **Friday** is the best day to release content
- 🎄 **December** is the best month for launches
- ⏳ Most content is added to Netflix **within 1–2 years** of release

---

## 💡 Business Recommendations
- Increase investment in **TV Shows**, especially in Asian markets
- Focus on **International and Drama-based content**
- Target **Friday & December** for major releases
- Prioritize **recent content acquisition** for better engagement
- Leverage repeating actors and directors for brand consistency

---

## 🛠 Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

---

## ✅ Outcome
This analysis converts raw OTT data into **actionable insights** that support **content planning, release strategy, and regional expansion** for streaming platforms.

