# Movie-ML-NLP-Recommendation-System
![jakob-owens-CiUR8zISX60-unsplash](https://github.com/vipra88/Movie-ML-NLP-Recommendation-System/assets/144676864/e3c9f1ff-ab98-4a65-8792-36b80935f4b4)



This repository contains the code and resources for analyzing the Movies dataset of movies and TV shows . The dataset was sourced from the third-party search engine Flixable and includes information about various attributes of the content available on Movies. The 
al of this project is to uncover insights, trends, and patterns within the dataset and develop a content-based recommender system using natural language processing (NLP) techniques.

## Problem Statement

The problem at hand involves exploring the Netflix dataset to gain insights into the content available on the platform. The dataset provides information about movies and TV shows, their attributes, and their availability in different countries. By integrating this dataset with external sources such as IMDB ratings and Rotten Tomatoes, we can extract further valuable information.

The specific tasks to be performed in this project include:

1. **Exploratory Data Analysis (EDA)**: Cleaned the data, unnested the Movies content and tackled the null/missing values and conduct a thorough analysis of the dataset to uncover trends, patterns, and correlations among different attributes.
2. **Understanding Content Availability**: Determine the types of content available in different countries and identify any variations or preferences.
3. **Analyzing Netflix's Focus**: Investigate whether Netflix has been increasingly focusing on TV shows rather than movies in recent years.
4. **Clustering Similar Content**: Utilize text-based features to cluster similar content, enabling the development of a content-based recommender system.

## Project Summary

The aim of this project is to analyze the Netflix dataset, which includes information on movies and TV shows available on the platform until 2019. With over 220 million subscribers, Netflix is the world's largest online streaming service provider. By analyzing and clustering the content, we can enhance the user experience through a personalized recommendation system, potentially reducing subscriber churn.

The project follows a step-by-step process, as outlined below:

1. **Handling Missing Values**: Address any null or missing values present in the dataset.
2. **Dealing with Nested Columns**: Process nested columns such as director, cast, listed_in, and country to facilitate clear visualization and analysis.
3. **Rating Binning**: Categorize ratings into appropriate categories, including adult, children's, family-friendly, and not rated content.
4. **Exploratory Data Analysis (EDA)**: Perform in-depth EDA on various attributes, uncovering valuable findings to aid in churn prevention.
5. **Cluster Creation**: Create clusters using attributes such as director, cast, country, genre, rating, and description. Tokenize, preprocess, and vectorize the attribute values using TF-IDF vectorizer.
6. **Dimensionality Reduction**: Reduce the dimensionality of the dataset using Principal Component Analysis (PCA) to improve performance.
7. **Clustering Algorithms**: Employ K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to construct two distinct types of clusters. Determine the optimal number of clusters using methods like the Elbow method, Silhouette score, and Dendrogram.
8. **Content-Based Recommender System**: Develop a content-based recommender system using the cosine similarity matrix. This system analyzes the user's watched shows and generates personalized recommendations to enhance their experience.
