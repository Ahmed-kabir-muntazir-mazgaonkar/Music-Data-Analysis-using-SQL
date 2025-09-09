# 🎵 Music Data Analysis using SQL  

## 📌 Project Overview  
This project focuses on analyzing **music-related data** using SQL queries.  
The goal is to extract meaningful insights about **artists, albums, tracks, and genres** from the dataset.  

## 🔹 Features  
- SQL queries to explore and analyze music data  
- Identified **most popular artists, albums, and songs**  
- Aggregated data to compare **music genres** and **user preferences**  
- Used **JOINS, GROUP BY, HAVING, and Subqueries** for advanced analysis  
- Focused only on **SQL (no external programming language used)**  

## 🛠️ Tech Stack  
- **Language:** SQL  
- **Database:** PostgreSQL / MySQL  

## 📊 Example Queries  
- Find the most streamed artist:  
  ```sql
  SELECT artist, COUNT(*) AS total_streams
  FROM music_data
  GROUP BY artist
  ORDER BY total_streams DESC
  LIMIT 1;
