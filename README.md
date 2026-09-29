# 🎬 Netflix Data Analysis using Python

<p align="center">
  
<p align="center">
  <b>Exploratory Data Analysis • Data Cleaning • Visualization • Business Insights</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white">
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white">
</p>

---
## 📌 Project Overview

This project analyzes a Netflix content dataset using **Python and Pandas** to understand the distribution and characteristics of Netflix Movies and TV Shows.

The analysis covers data cleaning, content type distribution, country-wise content, release-year trends, genres, ratings, visualizations, and business insights.

---
## 🎯 Objectives

- Clean and prepare the Netflix dataset
- Analyze Movies vs TV Shows
- Analyze Netflix content by country
- Identify release-year trends
- Analyze content ratings
- Identify the most common genres
- Compare ratings across Movies and TV Shows
- Create meaningful visualizations
- Generate actionable business insights

---
## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| 🐍 Python | Data analysis and programming |
| 🐼 Pandas | Data manipulation and analysis |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 📈 Plotly | Interactive visualization |
| 📓 Jupyter Notebook | Analysis environment |

---
# 📊 Analysis Performed

## 1️⃣ Data Cleaning & Preparation

The dataset was analyzed and prepared using Pandas.

### Cleaning activities:

- Checked missing values
- Identified duplicate records
- Checked formatting consistency
- Standardized missing country values
- Verified content types and ratings
- Exported the cleaned dataset

### Dataset Size

- **Total Records:** 8,790
- **Total Columns:** 10

---
## 2️⃣ Content Type Analysis

The distribution of Movies and TV Shows was analyzed.

| Content Type | Titles | Percentage |
|---|---:|---:|
| 🎬 Movies | 6,126 | 69.69% |
| 📺 TV Shows | 2,664 | 30.31% |
| **Total** | **8,790** | **100%** |

### Key Finding

Movies represent the majority of titles in the dataset, accounting for approximately **69.69%** of the total content.

---
## 3️⃣ Country-Wise Content Analysis

Netflix content was analyzed based on country.

### Top 5 Countries

| Rank | Country | Titles |
|---:|---|---:|
| 1 | 🇺🇸 United States | 3,240 |
| 2 | 🇮🇳 India | 1,057 |
| 3 | 🇬🇧 United Kingdom | 638 |
| 4 | 🇵🇰 Pakistan | 421 |
| 5 | 🇨🇦 Canada | 271 |

### Key Finding

The United States has the highest number of titles in the dataset, followed by India and the United Kingdom.

The dataset contains content from multiple countries, showing a broad international content presence.

---
## 4️⃣ Release Year Trend Analysis

The number of Netflix titles by release year was analyzed to identify content trends over time.

### Key Findings

- The dataset shows an overall increasing trend in recorded content over the years.
- A noticeable increase appears after 2000.
- Content growth becomes more prominent after 2015.
- **2018 recorded the highest number of titles.**
- **1,146 titles** were recorded for the year 2018.

> Note: The decline in recorded titles after 2018 reflects the available records in this dataset and should not by itself be interpreted as an actual decline in Netflix production.

---
## 5️⃣ Rating Analysis

Content ratings were analyzed to understand the rating distribution across the Netflix catalog.

### Top Ratings

| Rank | Rating | Titles |
|---:|---|---:|
| 1 | TV-MA | 3,205 |
| 2 | TV-14 | 2,157 |
| 3 | TV-PG | 861 |
| 4 | R | 799 |
| 5 | PG-13 | 490 |

### Key Finding

**TV-MA** is the most common rating in the dataset, followed by **TV-14**.

---
## 6️⃣ Genre Analysis

Multiple genres were extracted from the `listed_in` column and analyzed individually.

### Top 10 Genres

| Rank | Genre | Titles |
|---:|---|---:|
| 1 | 🌎 International Movies | 2,752 |
| 2 | 🎭 Dramas | 2,426 |
| 3 | 😂 Comedies | 1,674 |
| 4 | 🌎 International TV Shows | 1,349 |
| 5 | 📚 Documentaries | 869 |
| 6 | ⚔️ Action & Adventure | 859 |
| 7 | 📺 TV Dramas | 762 |
| 8 | 🎬 Independent Movies | 756 |
| 9 | 👨‍👩‍👧 Children & Family Movies | 641 |
| 10 | ❤️ Romantic Movies | 616 |

### Key Finding

**International Movies** are the most common genre category in the dataset, followed by **Dramas** and **Comedies**.

---
## 7️⃣ Rating Comparison: Movies vs TV Shows

Ratings were compared across Movies and TV Shows using a cross-tabulation analysis.

### Selected Findings

- TV-MA:
  - Movies: **2,062**
  - TV Shows: **1,143**
- TV-14:
  - Movies: **1,427**
  - TV Shows: **730**
- TV-Y:
  - Movies: **131**
  - TV Shows: **175**
- TV-Y7:
  - Movies: **139**
  - TV Shows: **194**

An **interactive Plotly visualization** was created to compare rating distributions across content types.

---

# 💡 Key Business Insights

### 📌 Content Portfolio

Movies make up the majority of the Netflix catalog represented in this dataset, accounting for **69.69%** of titles.

### 🌍 International Content

International content categories have a significant presence, with **International Movies** being the largest genre category.

### 🎭 Genre Distribution

Dramas and Comedies are among the most common genre categories, indicating a diverse content portfolio across entertainment categories.

### 🔞 Rating Distribution

TV-MA and TV-14 are the two most common rating categories in the dataset.

### 📅 Release Trends

The number of recorded titles increased significantly during the 2010s, with **2018** being the peak release year in the dataset.

### 🌎 Geographic Distribution

The United States has the highest number of titles, while India and the United Kingdom are also major contributors.

---

# 📈 Actionable Business Recommendations

### 1. Content Portfolio Planning

Monitor the balance between Movies and TV Shows to understand catalog composition and support future content planning.

### 2. International Content Strategy

Analyze international content by country, genre, and rating to identify opportunities for regional content expansion.

### 3. Genre Strategy

Monitor high-volume categories such as International Movies, Dramas, and Comedies when evaluating future content categories.

### 4. Audience Segmentation

Combine rating and genre information to understand different content segments and support targeted content planning.

### 5. Trend Monitoring

Track release-year trends regularly to identify changes in catalog composition and support data-driven planning.

---

