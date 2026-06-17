# Netflix Dataset Analysis 🎬

Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset, uncovering trends in content type, release patterns, and country-wise distribution.

## 📌 Overview

This project analyzes a dataset of **8,807 Netflix titles** to understand:
- How content has grown on the platform over the years
- The split between Movies and TV Shows
- Seasonal trends in when titles are added
- Which countries produce the most Netflix content

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – data cleaning and manipulation
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations

## 📂 Project Structure

```
netflix-analysis/
├── netflix_analysis.ipynb   # Main analysis notebook
├── net.csv                  # Dataset (Netflix titles)
└── README.md
```

## 🔍 Key Steps

1. **Data Loading & Inspection** – Checked dataset shape, column types, and missing values
2. **Data Cleaning** – Filled missing values in `country`, `cast`, and `director` columns
3. **Visualization** – Created charts to explore:
   - Number of titles added per year
   - Movies vs TV Shows distribution
   - Titles added by month (seasonality)
   - Top 10 countries by number of titles

## 📊 Sample Insight

The analysis reveals that content additions to Netflix grew significantly in recent years, with the **United States** and a handful of other countries dominating the platform's content library.

## 🚀 How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/ParvathySanthosh2005/data-analytics.git
   ```
2. Install dependencies
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the notebook
   ```bash
   jupyter notebook netflix_analysis.ipynb
   ```

## 📈 Future Improvements

- Add genre-based analysis using the `listed_in` column
- Explore rating distribution across content types
- Build an interactive dashboard using Plotly or Streamlit

---
*Part of my data analytics portfolio.*
