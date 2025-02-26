Netflix Data Analysis 

Project Overview  

This project analyzes a **Netflix dataset** containing **9,827 movies** with **9 key features**. The objective is to **clean, preprocess, and explore the data** to identify patterns related to **genres, popularity, votes, and release trends**.  

Dataset Preprocessing  
- ✅Checked for missing and duplicate values** → No NaNs or duplicates found.  
- ✅Converted `Release_Date` column** → Extracted the **year** and formatted it as `datetime`.  
- ✅Dropped unnecessary columns** → Removed `overview`, `original_language`, and `Poster_URL`.  
- ✅ Handled outliers** → Identified extreme values in the `popularity` column.  
- ✅ ategorized `vote_average`** → Grouped into **4 categories**:  
  - Popular  
  - Average  
  - Below Average  
  - Not Popular  
- ✅ Processed `Genre` column** → Cleaned whitespace, split multiple genres, and categorized properly.  
- ✅ Exploded `Genre` column** → Each row now represents a **single genre per movie**.  

Exploratory Data Analysis (EDA)  

 Key Insights  

 Most Frequent Genre**  
rama** is the most common genre, appearing in **14%** of the dataset.  

 Genre with the Highest Votes**  
- 5.5% of movies received a high number of votes (*,520 rows**).  
- Drama** dominates, receiving **18.5× more votes** than the average genre.  

** Most Popular Movie**  
- "Spider-Man: No Way Home"** is the most popular movie in the dataset.  
- Genres: Action, Adventure, Science Fiction**.  

* Least Popular Movie
- *Threads" is the least popular movie in the dataset.  
- Genres: Music, Drama, War, Sci-Fi.  

** Year with the Most Released Movies**  
- **2020 had the highest number of movie releases.  

## Conclusion & Future Work 
This analysis provided valuable insights into **Netflix movie trends**, including **popular genres, high-rated movies, and voting patterns**.  

### Future Improvements:  
- **Sentiment analysis** on movie reviews.  
- Predicting movie success** based on genre, votes, and popularity.  
- Comparing trends over multiple years for deeper insights.  
