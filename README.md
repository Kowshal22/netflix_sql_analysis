![](https://github.com/Kowshal22/netflix_sql_analysis/blob/main/logo%20(1).png)
# 🎬 Netflix SQL Analysis Project

## 📘 Overview
This project focuses on analyzing the **Netflix Titles Dataset** using **SQL**.  
It explores trends, patterns, and insights about Netflix content, including:
- The number of movies vs TV shows  
- Most common ratings  
- Top contributing countries  
- Yearly release trends  
- Director and actor analysis  
- Keyword-based content categorization  

---

## 🧰 Tools & Technologies Used
- **SQL** (PostgreSQL / MySQL compatible syntax)
- **Netflix Dataset (Kaggle)** — contains details such as title, director, cast, country, release year, duration, and more.
- **PostgreSQL Functions** like `UNNEST`, `STRING_TO_ARRAY`, `SPLIT_PART`, `ILIKE`, and window functions (`RANK()`).

---
## Questions Solved
1. Count the number of Movies vs TV Shows
2. Find the most common rating for movies and TV shows
3. List all movies released in a specific year (e.g., 2020)
4. Find the top 5 countries with the most content on Netflix
5. Identify the longest movie
6. Find content added in the last 5 years
7. Find all the movies/TV shows by director 'Rajiv Chilaka'!
8. List all TV shows with more than 5 seasons
9. Count the number of content items in each genre
10.Find each year and the average numbers of content release in India on netflix. 
11. List all movies that are documentaries
12. Find all content without a director
13. Find how many movies actor 'Salman Khan' appeared in last 10 years!
14. Find the top 10 actors who have appeared in the highest number of movies produced in India.
15.Categorize the content based on the presence of the keywords 'kill' and 'violence' in the description field. Label content containing these   keywords as 'Bad' and all other content as 'Good'. Count how many items fall into each category.

## 📈 Insights
- Movies dominate over TV Shows on Netflix.
- **TV-MA** and **TV-14** are the most frequent ratings.
- **United States**, **India**, and **United Kingdom** have the most content.
- India shows consistent yearly content growth.
- Certain keywords in descriptions correlate with mature-rated content.

---
