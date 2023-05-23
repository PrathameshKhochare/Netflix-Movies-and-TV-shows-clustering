# Netflix-Movies-and-TV-shows-clustering
## Introduction -:
Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages.
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/42363a54-bf86-46d1-8453-48d192016d97)

# Problem Statement -:
The goal of this project is to find similarity within groups of people to build a movie recommendation system for users. We are going to analyze a dataset from the Netflix database to explore the characteristics that people share in movies. We have experienced it ourselves or have been in the room, the endless scrolling of selecting what to watch. Users spend more time deciding what to watch than watching their movie.
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/26b77ec0-1983-45ec-b654-7eb6b4fada67)

# Data Summery -:
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

show_id : Unique ID for every Movie / Tv Show
type : Identifier - A Movie or TV Show
title : Title of the Movie / Tv Show
director : Director of the Movie
cast : Actors involved in the movie / show
country : Country where the movie / show was produced
date_added : Date it was added on Netflix
release_year : Actual Release Year of the movie / show
rating : TV Rating of the movie / show
duration : Total Duration - in minutes or number of seasons
listed_in : Genere
description: The Summary description
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/1f8b6a2d-1440-4dfe-aae6-19956fd08b39)

# Workflow :
1. Know Your Data
2. Understanding your Data
3. Data Wrangling
     * Handling null values
     * Handling duplicate values
     * Removing Outliers
     * Feature engineering
     * Binning
     * Typecasting
4. Data Vizualization, Storytelling & Experimenting with charts : Understand the relationships between variables
    * Univariate
    * Bivariate
    * Multivariate
5.Hypothesis Testing
6.Feature Engineering & Data Pre-processing
    1.Handling Missing Values
    2.Textual Data Preprocessing
         * Expand Contraction
         * Lower Casing
         * Removing Punctuations
         * Removing URLs & Removing words and digits contain digits.
         * Removing Stopwords & Removing White spaces
         * Tokenization
         * Text Normalization
         * Part of speech tagging
         * Text Vectorization
    3.Dimesionality Reduction
    
7.ML Model Implementation

         * K-Means Clustering
         * Hierarchial Clustering
         * DBSCAN
         * Recommendaton System
         
8.Conclusion

9.Future Work        
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/1f8b6a2d-1440-4dfe-aae6-19956fd08b39)

For further information you can check the google colab file added in the repository.

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - khochareprathamesh10@gmail.com
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/1f8b6a2d-1440-4dfe-aae6-19956fd08b39)

# Conclusion:

**1. Conclusions Drawn from EDA -:**
Based on the exploratory data analysis (EDA) of the Netflix movies and TV shows clustering dataset, we have drawn the following conclusions:

* The Netflix dataset contains a larger percentage of **movies (70%)** compared to **TV shows (30%)**.
* **Jan Suter** is the most common **movie director** on Netflix, while **Alastair Fothergill** is the most common **TV show director**.
* Indian actors dominate the movies on Netflix, while there are no popular Indian actors in the TV shows.
* **Anupam Kher** is the most common **movie actor** on Netflix, while **Takahiro Sakurai** is the most common **TV show actor**.
* The majority of Netflix **movies genres** are **documentaries followed by Stand-Up-Comedy**, whereas the most popular category for Netflix **TV shows is kid's TV**.
* **United States** is the largest producer of both **movies and TV shows** on Netflix, followed by India, which is the largest producer of movies.
* **Japan, South Corea** has more **TV Shows** with respect to movies.
* Most of the Netflix content own by **US and UK**.
* Netflix bussiness starts to rise from year **2015**.
* The trend in Netflix content has been a significant increase in the number of TV shows since 2018, accompanied by a decline in the number of movies. Additionally, the number of movies added in 2020 was lower compared to 2019, while the number of TV shows added in 2020 was higher than in 2019.
* **October to January** are the peek months of Netflix **Movie's** bussiness and **October to December** are the peek months for **TV Shows**. the one of the reason may be as Netflix has most audience/content from US/UK based and October-January are vacation months in US (Thanksgiving,Christmas,New Year)
* Most of the movies and TV shows are added at the **beginning , middle and end** of the month. It could be because most people have tendency to watch new content at the start/end of the montly plan. some people might choose their plan at the middle of the months.releasing new content during that time could increase viewership.
* The majority of movies on Netflix have a duration between **80 to 120** minutes, while the most common duration for TV shows is **one season**, followed by two seasons.
* **Adult and teen** categories are the most prevalent on Netflix, with **family-friendly** content being more common in **TV shows** than in movies.
* Most countries produce content related to **adult and teen** categories, with **India** having **less adult** content than teen content. Spain produces the most adult content, while **Canada** produces more content related to **children and family-friendly** categories.

**2.Conclusions drawn from ML Model -:**

We have implimented 4 models for ML

1. K-means clustering
2. Agglomerative Hierarchical Clustering
3. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
4. Recommendaton System

* The **optimal number** of clusters we are getting from **K-means is 4**, whereas for **Agglomerative Hierarchical Clustering** the optimal number of clusters are found out to be **3**.
* We chose **Silhouette Score** as the evaluation metric over **distortion score** because it provides a more intuitive and interpretable result. Also Silhouette score is less sensitive to the shape of the clusters.
* DBSCAN algorithm failed to differenciate clusters and hence not helped in our Project. 
* Built a **Recommendation system** that can help Netflix improve user experience and reduce subscriber churn by providing personalized recommendations to users based on their similarity scores.
![image](https://github.com/PrathameshKhochare/Netflix-Movies-and-TV-shows-clustering/assets/121234763/1f8b6a2d-1440-4dfe-aae6-19956fd08b39)
