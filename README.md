# 🎬 Netflix Movie Ratings Analysis

This report explores the distribution of movie ratings on Netflix, the countries and genres involved, and how different factors correlate with average ratings.

---

## 1. Rating Distribution

Most Netflix movies have ratings between **6.0 and 6.5**, as shown in the distribution below.

![Rating Distribution](images/distribution_of_rating.png)

---

## 2. Top 10 Countries by Number of Films

The **United States** dominates with nearly **8,000 movies**, far ahead of the second-place country.
Here’s the full top 10:

1. United States
2. United Kingdom
3. France
4. Canada
5. Japan
6. South Korea
7. Germany
8. Spain
9. India
10. Belgium

Only the top 6 countries produced over 1,000 films.

![Top Countries](images/top10_countries.png)

---

## 3. Most Common Genres

The most frequent genre is **Drama**, with almost **7,000 titles**, followed by:

- Comedy: ~4,500
- Thriller: ~4,000
- Action: >3,000
- Romance & Horror: >2,000
- Adventure, Crime, Animation, Family: <2,000

![Top Genres](images/top10_genres.png)

---

## 4. Average Rating by Genre

Only two genres have average ratings above **7.0**:
- 🎵 Music
- 📽️ Documentary

All others fall between **6.0 and 7.0**, except for **Horror**, which is the only one **below 6.0**.

![Average Rating by Genre](images/avg_rating_by_genre.png)

---

## 5. Correlation Between Votes and Ratings

A scatterplot with a regression line shows a clear trend:
➡️ **More votes → Higher average rating**

![Votes vs Rating](images/votes_vs_rating.png)

---

## 6. Average Rating Over Time (2010–2025)

Between 2010 and 2013, the average rating stayed near **6.1–6.2**.
From 2014 to 2019, it steadily increased, peaking at **6.5 in 2021**.
Recent years (2024–2025) show a slight decline, with 2025 having the **lowest average**, although data is still incomplete.

![Rating Over Time](images/rating_over_time.png)

---

## 7. Top 10 Countries by Average Rating

All countries in this list have an average rating **above 6.0 and below 7.0**:

1. Japan
2. Mexico
3. Brazil
4. Denmark
5. Sweden
6. Norway
7. China
8. Germany
9. Switzerland
10. India

![Top Countries by Rating](images/top10_countries_by_rating.png)

---

## 8. Rating vs. Number of Movies by Country

This chart highlights outliers:

- 🇯🇵 **Japan** has a high rating (>6.75) with a typical number of films
- 🇵🇭 **Philippines** has a **much lower rating** (~5.0) despite average output
- 🇺🇸 **USA** has a standard rating (~6.25) but an **exceptionally large** number of films

All other countries fall between 100–2,000 films and ratings between 6.0–6.75.

![Rating vs Movie Count](images/rating_vs_num_movies.png)

---

## 9. Top 10 Highest Rated Movies (min. 100 votes)

All movies in this list have a rating above **8.0**.
Three titles share the top spot with a rating of **8.5**:

1. Your Name
2. Interstellar
3. Parasite
4. Gabriel’s Inferno
5. Wishplay
6. Gabriel’s Inferno Part II
7. A Silent Voice
8. Gabriel’s Inferno Part III
9. Spider-Man: Into the Spider-Verse
10. Inception

![Top 10 Movies](images/top10_movies.png)

---

## 10. Notes

- Co-productions were split by country.
- Only countries with at least 100 films were included in the rating-country analysis.
- Outliers are intentionally highlighted to show how volume and quality can diverge.

---

## 👨‍💻 Author

Raffaele (2025)
Python + SQL | Data Exploration Project
