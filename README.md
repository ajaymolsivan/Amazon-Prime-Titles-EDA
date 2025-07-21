# 📊 Amazon Prime Titles EDA

> Exploratory Data Analysis on Amazon Prime Video Titles and Credits Data

---

## 📁 Project Type
EDA (Exploratory Data Analysis)

## 👤 Contribution
Individual

## 📝 Project Summary

This project performs an in-depth Exploratory Data Analysis (EDA) on Amazon Prime's content catalog, focusing on both movie and show titles. The goal is to uncover trends, patterns, and insights from metadata such as genres, ratings, release years, runtimes, and cast details.

The analysis includes:
- Univariate, Bivariate, and Multivariate visualizations
- Score distributions from IMDb and TMDB
- Genre frequency and performance
- Trends across years and certifications
- Actor and crew contributions
- Business-focused insights and recommendations

A total of **20+ well-commented and logically structured charts** were created.

---

## 🧠 Problem Statement

Amazon Prime hosts a vast and diverse content library. Understanding which factors contribute to a title's success — such as genre, rating, runtime, and cast — is crucial for content acquisition, recommendation engine optimization, and audience targeting.

---

## 🎯 Business Objective

To identify key patterns and trends in Amazon Prime titles that help improve:
- Content acquisition strategies
- Audience segmentation and targeting
- Investment in high-performing genres and cast
- Platform recommendations and user engagement

---

## 🗂️ Dataset Description

Two datasets were used:

### `titles.csv`
Contains metadata about Amazon Prime titles:
- `id`, `title`, `type`, `description`, `release_year`, `age_certification`, `runtime`, `genres`, `production_countries`, `seasons`, `imdb_score`, `imdb_votes`, `tmdb_score`, `tmdb_popularity`

### `credits.csv`
Contains cast and crew details:
- `id`, `name`, `role`

---

## 🔧 Data Cleaning & Manipulation

- Parsed stringified lists in `genres` and `production_countries`
- Handled missing values and checked for duplicates
- Converted appropriate columns to allow filtering and aggregation
- Grouped and analyzed numeric metrics (scores, runtime, years)

---

## 📈 Key Visualizations

The notebook includes visualizations across:

- **Univariate**: Content types, ratings, genre frequencies
- **Bivariate**: IMDb score vs runtime, release year vs scores
- **Multivariate**: Heatmaps, boxplots, pairplots

All charts are labeled, justified, and followed by business insights.

---

## 💡 Insights & Recommendations

- Focus more on **Drama, Comedy, and Documentary** genres
- Expand offerings for **underrepresented age certifications** (e.g., PG, G)
- Prioritize **high IMDb/TMDB scoring titles** for marketing
- Use **top-performing cast members** in future productions
- Maintain runtime within optimal viewer-friendly ranges (60–120 min)

---

## ✅ Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Missingno
- Jupyter Notebook

---

