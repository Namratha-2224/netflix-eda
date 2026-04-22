# 🎬 Netflix EDA — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
Exploratory Data Analysis on Netflix Movies and TV Shows dataset from Kaggle.
The goal is to uncover patterns and trends in Netflix content using Python.

## 📂 Dataset
- Source: [Kaggle — Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- Rows: 8807 | Columns: 12
- Features: title, type, director, cast, country, date_added, rating, duration, listed_in

## 🛠️ Tools Used
- Python 3.11
- Pandas — data cleaning
- Matplotlib & Seaborn — visualizations
- Jupyter Notebook (VS Code)

## 📊 Visualizations & Insights

| # | Chart | Insight |
|---|-------|---------|
| 1 | Movies vs TV Shows | Netflix has more Movies than TV Shows |
| 2 | Top 10 Countries | USA dominates, followed by India & UK |
| 3 | Content Over Years | Massive growth from 2016–2019 |
| 4 | Top Ratings | TV-MA dominates — targets mature audience |
| 5 | Top Genres | International Movies & Dramas are biggest |
| 6 | Movie Duration | Most movies are 80–120 minutes |
| 7 | TV Show Seasons | Most shows have only 1 season |
| 8 | Content by Month | January & July see most additions |
| 9 | Top Directors | Jan Suter leads with most titles |
| 10 | Type vs Rating Heatmap | TV-MA highest across both types |

## 📁 Project Structure
```
netflix-eda/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── netflix_eda.ipynb
├── images/
│   └── (10 chart PNGs)
├── requirements.txt
└── README.md
```

## 🚀 How to Run
```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook notebooks/netflix_eda.ipynb
```