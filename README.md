# 🎯 Project Overview

# 🎬 Movie Recommendation System – Full Data Science Pipeline + GUI
This project demonstrates a complete data science pipeline on a movie dataset—from raw CSV to a fully working movie recommender web app. It uses NLP + EDA + GUI development to recommend movies based on keyword inputs.

# ✅ Summary of What I Did

# Step	Description

1. Data Cleaning	Removed nulls, duplicates, converted dates
2. Exploratory Analysis	Plotted distributions, trends, and data stats
3. Wordcloud Analysis	Generated common keyword cloud from overviews
4. Time Series Plotting	Trend of movie releases over years
5. TF-IDF Recommender	Built a model using movie overviews + cosine similarity

# 📌 Results & Insights

# 📉 Data Cleaning & Preparation
✔ Filled 253 missing overviews with empty strings
✔ Dropped 209 duplicate rows
✔ Converted release_date to datetime
✔ Dropped 156 rows with missing release_date

# 📊 Exploratory Data Analysis

# Distribution of Vote Average
1. Most movies have a rating between 5.0 and 7.5
2. Number of votes is skewed (few very high-voted films).
3. Most movies receive ratings between 5 and 8, showing a slight right skew.
4. A large number of movies have a zero vote average, likely due to missing or unrated entries.
5. The distribution follows a near-normal curve with a long tail toward the higher ratings.
![{DC370D43-11C2-4A4C-A3EB-1AC131B15D00}](https://github.com/user-attachments/assets/ec742b4f-ebdd-479a-9507-754e545accfb)

# Number of Movies Released Per Year
1. There is a consistent rise in movie production over time, especially after 2000.
2. A sharp spike is seen in the 2010s, suggesting data availability and global film output both increased.
3. Pre-1950s, very few movies are recorded—indicating either limited data or actual lower production.
![{0A1078ED-05C2-4917-ACB9-ED71B95DCD1F}](https://github.com/user-attachments/assets/b64a4fb4-182a-471f-99c3-3efe632268f6)

# Average Popularity Over Time¶
1. The 1940s and 2020s show sudden spikes, possibly due to outlier films with massive popularity scores.
2. Overall, popularity remains fairly stable with slight increases in the modern era, likely due to streaming and marketing reach.
3. A dip is observed post-2020, possibly due to the pandemic's impact on movie releases.
![{DCFD4836-EFDD-4882-85D6-60BAB74B5B7E}](https://github.com/user-attachments/assets/885044bd-44d0-498b-a4db-fe220eb36cf0)

# Top 10 Original Languages
1. English ('en') dominates the dataset with a huge margin.
2. Other common languages include Japanese, French, Korean, Chinese, and Spanish, reflecting global contributions.
3. This plot helps identify linguistic diversity and which markets are best represented.
![{110C4CED-5EF3-4810-839A-9F8891EEEACC}](https://github.com/user-attachments/assets/f6dd5a39-cea0-42e0-8b9c-08c0cccaee02)

# ☁️ Wordcloud of Movie Overviews
1. Generated a wordcloud showing the most common words across movie summaries.
2. Larger words indicate higher frequency.
![{6C138565-2EB1-4BE2-9C07-6B47CD35B429}](https://github.com/user-attachments/assets/49bfc104-d7ee-456c-83db-23f4768f4866)


# 🤖 Recommendation System (TF-IDF + Cosine Similarity)
1. Vectorized movie overviews using TfidfVectorizer
2. Compared input keyword with overviews using cosine_similarity
3. Returned top 10 matches

![Picture1](https://github.com/user-attachments/assets/085107ff-9a4d-4d73-93ac-4fc879c2a12c)
![Picture2](https://github.com/user-attachments/assets/f2ace0ed-14cd-4418-a235-28c4cf2f91d2)
![Picture3](https://github.com/user-attachments/assets/2615d412-8b69-4f06-b095-d2d1fb72a092)
![Picture4](https://github.com/user-attachments/assets/c0a0e231-710a-4894-9114-da0e49c2a53d)

1. Movie title in accent color and bold.
2. Ratings in golden color and italics.
3. Overview in clean, light text.
4. Divider lines for readability.

This colorful, themed desktop app brings NLP-powered movie recommendations to life in an easy-to-use GUI. It’s perfect for anyone who wants to discover movies simply by typing in free-form natural language queries.


