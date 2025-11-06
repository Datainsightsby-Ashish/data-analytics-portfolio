# Project 1 — EDA

### Netflix Catalog Analysis (EDA)

### Objective
Analyze Netflix’s catalog to uncover patterns in content type, audience targeting, country contribution, release trends, and growth.

### Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

### Key Questions
1. What’s the ratio of Movies vs TV Shows?  
2. Which audience categories dominate (ratings)?  
3. Which countries produce most Netflix titles?  
4. Are titles mostly recent or older?  
5. How has Netflix’s catalog grown over time?  
6. How do release years compare to year added?  
7. What are the top genres?

### Key Insights
- ~70% Movies, 30% TV Shows — shifting toward serial content.  
- Majority **TV-MA / TV-14** → adult/teen focus.  
- Dominated by **US**, **India**, **UK**, **Japan**, **Korea**.  
- Post-2010 releases dominate → modern catalog.  
- Rapid growth 2015–2019 → expansion phase.  
- Mix of new + old titles → back-catalog licensing.  
- Top genres: *International Movies*, *Dramas*, *Comedies* → emotional, global storytelling.

### Limitations
- Multi-country and multi-genre labeling may inflate counts.  
- `date_added` missing for a few entries.  
- No engagement/viewership data.

### Next Steps
- Analyze regional or genre trends over time.  
- Add viewership layer (if available).  
- Explore content clustering or recommendations.


## How to Run
1) Open in Google Colab.
2) Mount Drive.
3) Update the `path` to your file location if needed.
4) Run cells top-to-bottom.


## Folder Structure


01_EDA_Project/
│
├── Netflix_EDA.ipynb

├── README.md
├── netflix_titles.csv
└── figures/
├── 01_composition_movies_vs_tvshows.png
├── 02_audience_top_ratings.png
├── 03_country_top10.png
├── 04_release_year_distribution.png
├── 05_platform_growth.png
├── 06_release_vs_added_scatter.png
├── 07_type_trend_over_time.png
├── 08_top_genres.png



