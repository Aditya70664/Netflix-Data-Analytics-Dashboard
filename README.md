# 🎬 Movie & Streaming Content Analytics Dashboard

An interactive Power BI dashboard built to analyze movie and streaming-content data, focusing on ratings, popularity, audience engagement, genres, languages, and content trends over time.

---

## 📌 Project Overview

This project transforms a movie-content dataset into an interactive dashboard that makes it easier to explore content performance and identify useful patterns.

The dashboard brings key metrics and visual analysis together in one place, allowing users to explore the data using **Year** and **Genre** filters.

---

## 🎯 Objectives

- Analyze movie and streaming-content performance
- Identify highly rated titles
- Compare popularity across genres
- Analyze average IMDb ratings by genre
- Understand audience engagement through vote counts and ratings
- Track popularity trends over the years
- Analyze content growth over time
- Explore content distribution by language

---

## 📊 Dashboard Highlights

| KPI | Value |
|---|---:|
| High Rated Titles | **436** |
| Total Content | **10K** |
| Average IMDb Rating | **6.43** |
| Average Popularity | **40.32** |
| Average Vote Count | **1.39K** |

### Key Analysis

- Average Popularity by Genre
- IMDb Rating by Genre
- Content Distribution
- Language Distribution
- Vote Count vs. Average Rating
- Popularity Trend by Year
- Content Growth by Year

---

## 🖥️ Dashboard Preview

![Movie & Streaming Content Analytics Dashboard](Images/dashboard.png)

---

## 🔎 Interactive Filters

The dashboard allows users to explore the data using:

- **Year**
- **Genre**

These filters make it easier to compare different periods and content categories.

---

## 🗂️ Dataset

The dataset contains **9,837 records** with fields including:

- Release Date
- Title
- Overview
- Popularity
- Vote Count
- Vote Average
- Original Language
- Genre
- Poster URL

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **SQL** | Data analysis and business queries |
| **Python** | Data preparation and exploratory analysis |
| **Excel** | Source dataset |

---

## 📈 Analysis Performed

### Genre Analysis

Compared genres based on:

- Average popularity
- Average IMDb rating
- Content volume
- Audience engagement

### Rating Analysis

Analyzed:

- Average IMDb rating
- Highly rated titles
- Rating patterns across genres
- Relationship between ratings and votes

### Popularity Analysis

Examined:

- Average popularity by genre
- Popular titles
- Popularity trends across release years

### Audience Engagement

Used vote count and vote average to understand audience response to different titles.

### Time-Based Analysis

Analyzed:

- Content growth by year
- Popularity trends by year
- Changes in the content catalog over time

### Language Analysis

Explored the distribution of content across original languages.

---

## 💡 Business Questions

The project helps answer questions such as:

1. Which genres have the highest average popularity?
2. Which genres have the strongest average IMDb ratings?
3. How many titles are classified as highly rated?
4. How does audience voting relate to average ratings?
5. How has content volume changed over the years?
6. How has popularity changed across release years?
7. How is content distributed across languages?
8. Which genres and years show stronger content performance?

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Inspection & Preparation
     ↓
Python / SQL Analysis
     ↓
Data Transformation
     ↓
Power BI Dashboard
     ↓
Interactive Analysis & Insights


Movie-Streaming-Content-Analytics/
│
├── README.md
│
├── Dashboard/
│   └── Movie_Streaming_Content_Analytics.pbix
│
├── Data/
│   └── mymoviedb.csv.xlsx
│
├── SQL/
│   └── SQL_Analysis.sql
│
├── Python/
│   └── Data_Analysis.ipynb
│
├── Documentation/
│   ├── Business_Problem_Statement.pdf
│   ├── Project_Report.pdf
│   └── SQL_Analysis.pdf
│
└── Images/
    └── dashboard.png

Author

Aditya Sharma

Data Analytics | SQL | Python | Power BI

📧 Email: adityasha233@@example.com

---

