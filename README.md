# 🎬 IMDb Top 250 Data Analytics Dashboard

An interactive Power BI dashboard designed to analyze and uncover patterns within the top-rated 250 movies in cinema history, spanning from 1921 to 2025. This project focuses on data distribution across different cinematic eras, voter engagement, and the correlation between movie runtimes and ratings.

---

## 📊 Dashboard Previews

### Page 1: Overview & Time-Series Analysis
![Overview Dashboard](Screenshots/image_a3b2d8.png)
<img width="1298" height="727" alt="Screenshot 2026-07-02 213241" src="https://github.com/user-attachments/assets/41990397-33a8-4e14-9ae4-d999742db090" />

### Page 2: Correlation & Engagement Insights
![Correlation Dashboard](Screenshots/image_a3b31b.png)

---

## 📈 Key Dashboard Features & Insights

* **Core Metrics at a Glance:** Tracks a total of **250 movies** with an overall **Average Rating of 8.31** and a massive **Total Engagement of 188M+ votes** across the dataset.
* **Cinematic Eras Segmentation:** Categorized movies into distinct eras (*Old Era*, *Golden Classic Era*, and *New Era*) using custom DAX, showing that the *New Era* holds the largest share with **42.8% (107 movies)**.
* **Advanced Correlation Analysis:** 
  * Built a custom Scatter Plot to map movie distribution by Era, Number of Votes, and Rating.
  * Developed a Bubble Chart analyzing **Average Rating Over Run Time And Viewership**, proving how audience engagement scales with longer runtimes (up to a Max Run Time of **374 minutes**).
* **Time-Series Insights:** Dual line charts tracking both the historical trajectory of *Average Ratings Over Time* and the density of *Movies per Year*.

---

## 🛠️ Tech Stack & Skills Demonstrated

* **Tool:** Microsoft Power BI / Power Query
* **DAX Engineering:** Custom time-intelligence, filtering metrics, and dynamic conditional logic for Era leadership.
* **UI/UX Design:** Implemented a highly scannable, customized dark theme aligned with IMDb’s official branding to improve user experience and visual hierarchy.

---

## 🚀 How to View the Project
1. Download the `Movie_imdb.pbix` file from this repository.
2. Open it using **Power BI Desktop**.
