# 📊 Netflix Data Analysis

This project explores the **Netflix Titles Dataset** (`netflix_titles.csv`) using Python and Jupyter Notebook. The dataset contains information about Movies and TV Shows available on Netflix, including details like title, type, release year, duration, content rating, and country of origin.

The analysis provides **insights into Netflix’s content trends**, such as:

## 🔎 Key Insights & Visualizations

1. **Percentage of Content Ratings**
   ![Content Rating Pie](content_Rating_pie.png)

   * TV-MA (36.8%) and TV-14 (24.2%) dominate Netflix’s content.
   * Family/children-friendly ratings (TV-Y, PG, G) make up only a small fraction.

2. **Distribution of Movie Durations**
   ![Movie Duration Histogram](movie_duration_hist.png)

   * Most movies are between **80–120 minutes**, peaking around \~95 minutes.
   * Very few movies go beyond 200 minutes.

3. **Comparison of Movies vs TV Shows Released Over the Years**
   ![Movies vs TV Shows](movie_tv_shows_comparison.png)

   * Steady rise after 2000, with a sharp increase post-2010.
   * Movies (blue) are consistently higher, but TV shows (red) have grown rapidly in the last decade.

4. **Number of Movies vs TV Shows on Netflix**
   ![Movies vs TV Shows Bar](movie_vs_Tvshows.png)

   * Movies: \~5700
   * TV Shows: \~2300
   * Movies dominate the platform with more than double the count of TV shows.

5. **Release Year vs Number of Shows**
   ![Release Year Scatter](release_year_scatter.png)

   * Explosion of new content after 2010, especially in 2018–2020.
   * 2020 marks one of the highest peaks in Netflix releases.

6. **Top 10 Countries by Number of Shows**
   ![Top Countries](top10_countries.png)

   * United States leads with **2800+ shows**, followed by India (\~1000).
   * UK, Japan, South Korea, and Canada are other major contributors.

---

## 🛠️ Tech Stack

* **Python** 🐍
* **Libraries**: Pandas, Matplotlib
* **Jupyter Notebook** for data exploration (`netflix.ipynb`)
* Dataset: [`netflix_titles.csv`](netflix_titles.csv)

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/netflix-analysis.git
   cd netflix-analysis
   ```
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook netflix.ipynb
   ```

---

## 📌 Conclusion

* Netflix has a **huge dominance of Movies over TV Shows**.
* Most movies have a **runtime of 1.5–2 hours**.
* The majority of content is **mature audience-focused (TV-MA, TV-14)**.
* **United States and India** contribute the largest share of Netflix content.
* There was a massive growth in Netflix releases after **2010**, with a peak around **2018–2020**.

---

👉 This project provides a **data-driven overview of Netflix’s catalog** and can be extended with recommendations, genre analysis, or trend forecasting.

---
