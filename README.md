# Netflix Content Strategy Analysis 🎬
**Exploratory Data Analysis (EDA) on Netflix dataset using Python**

## 📌 Executive Summary
This project provides a comprehensive Exploratory Data Analysis (EDA) of the Netflix dataset. The goal was to uncover patterns in content production, audience targeting, and global distribution to understand how Netflix maintains its position as a market leader.

## 🚀 Key Insights & Findings

### 1. Content Dominance: Movies vs. TV Shows
* **Insight:** Approximately **70%** of Netflix’s library consists of Movies, while TV Shows account for **30%**.
* **Business Takeaway:** While Movies dominate in volume, there is a noticeable upward trend in TV Show production in recent years, likely aimed at increasing user retention (binge-watching).
* 
<img width="482" height="507" alt="type_ratio" src="https://github.com/user-attachments/assets/c36612b4-46fb-45ac-b135-231a665cbd3c" />

### 2. Audience Targeting
* **Insight:** The majority of Netflix content is rated **TV-MA** (Adults) and **TV-14** (Teens).
* **Business Takeaway:** Netflix heavily prioritizes adult and teenage demographics, tailoring its content to more mature storytelling which aligns with global streaming trends.
<img width="1394" height="450" alt="rating" src="https://github.com/user-attachments/assets/28a350e7-da4f-4e02-af8b-dfd614b3d900" />

### 3. TV Show Longevity & Retention
* **Insight:** Analysis reveals that only **32.77%** of TV Shows proceed beyond the first season.
* **Business Takeaway:** This suggests a "fail-fast" strategy where Netflix aggressively tests new pilots but only invests in multiple seasons for high-performing titles.

### 4. Global Production Hubs
* **Insight:** The United States remains the primary content producer, followed by India and the United Kingdom.
* **Trend:** India shows a unique pattern with a much higher ratio of Movies compared to TV Shows, reflecting the strong Bollywood cinema culture.
<img width="580" height="554" alt="country_content" src="https://github.com/user-attachments/assets/f621b0a4-6c35-4ee3-817a-28667e8f6107" />

### 5. Content Categorization
* **Insight:** International Movies, Dramas, and Comedies are the most frequent genres.
* **Observation:** Netflix’s heavy investment in "International" categories highlights its strategy for global localization—producing content in local languages to capture non-English speaking markets.
<img width="1394" height="450" alt="genre" src="https://github.com/user-attachments/assets/9558da62-a8cb-42cd-9e6e-61fefeac3e7a" />

## 🛠️ Technical Highlights (Data Engineering Focus)
* **Data Cleaning:** Handled significant missing values in director and cast columns using logical imputation (e.g., mode-based filling and "No Data" labels).
* **Feature Engineering:** * Parsed and transformed the `duration` column to separate numeric values for Movies (minutes) and TV Shows (seasons).
* Utilized the `explode` function to analyze multi-valued attributes like `cast` and `listed_in`.
* **Visualizations:** Created interactive dashboards and charts using **Plotly Express** and **Seaborn** for dynamic data exploration.

## 💡 Recommendations for Netflix
* **Diversify for Kids:** While adult content is high, there is a growth opportunity in expanding the "Kids" category to compete with platforms like Disney+.
* **Nurture Long-form Content:** Increasing the renewal rate for TV Shows could help stabilize subscription churn.


