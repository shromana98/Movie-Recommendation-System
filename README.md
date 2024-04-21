# Movie-Recommendation-System
## 🎯Objective: 
" 🎬Movie Recommendation System! 🎥"
In this implementation, when the user searches for a movie it will recommend the top similar movies using the movie recommendation system. I have used  a content based filtering algorithm for this purpose. 

## 🔍 Data Cleaning:
(TMDB Movie dataset Source: Kaggle) the first task was to browse all the data and replace the json character in string format using the json.loads() method.
Dealt with the null values, duplicates, zero values, data type of columns. 

 ## 📊 Exploratory Data Analysis (EDA) :

## 💡 Insights:

-Profit and Popularity shows a positive but low correlation.
-Wednesday emerges as the day with the highest average profit and popularity, while Friday lags behind.
-Majority of movies the revenues increases when the rating increase
-The rating of movies increases especially when the number of actors is around 6 and 7 main actors and in most of the cases the revenue increases when the number of actors increases.
-Medium films steal the spotlight, consistently outperforming other categories in terms of average profits.
-Short films exhibit increasing profit trends, with 2015 and 2016 surpassing the overall profit mean.
-Long films garner the highest average vote ratings in 2009.
-Action genre reigns supreme in revenue generation, with iconic movies like Avatar setting the bar high.
-Warner Bros emerges as the top production company, leading the pack in the number of movies released.
-Despite the dominance of male-centric narratives, there's potential for diversification and inclusivity in the industry.


 # To build the recommendation system:
1. Data Preprocessing: Selected relevant columns and applied stemming to standardize text data for analysis.
2. CountVectorizer: Utilized CountVectorizer to convert textual data into numerical vectors, facilitating analysis and recommendation.
3. Algorithm: Employed content based filtering techniques to generate personalized recommendations based on user preferences.



