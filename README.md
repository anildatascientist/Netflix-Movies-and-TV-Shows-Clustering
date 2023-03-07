![harrypotty-min-1-768x471](https://user-images.githubusercontent.com/59911959/195928205-b790fb3c-f702-4dc2-9a7c-12b1da6287e1.jpg)

# NETFLIX MOVIES AND TV-SHOWS-CLUSTERING

## 📋 Abstract:
Netflix is a company that manages a large collection of TV shows and movies, streaming them anytime online. This business is profitable because users make a monthly payment to access the platform. However, customers can cancel their subscriptions at any time. Therefore, the company must keep the users hooked on the platform and not lose their interest. This is where recommendation systems start to play an important role, providing valuable suggestions to users is essential.

## Introduction:
Netflix’s recommendation system helps them increase their popularity among service providers as they help increase the number of items sold, offer a diverse selection of items, increase user satisfaction, as well as user loyalty to the company, and they are very helpful in getting a better understanding of what the user wants. Then it’s easier to get the user to make better decisions from a wide variety of movie products. With over 139 million paid subscribers (total viewer pool -300 million) across 190 countries, 15,400 titles across its regional libraries, and 112 Emmy Award Nominations in 2018 — Netflix is the world’s leading Internet television network and the most-valued largest streaming service in the world. The amazing digital success story of Netflix is incomplete without the mention of its recommender systems that focus on personalization. There are several methods to create a list of recommendations according to your preferences. You can use (Collaborative-filtering) and
(Content-based Filtering) for recommendation.

## 🎯 Business Requirement:
Netflix Recommender recommends Netflix movies and TV shows based on a user's favourite movie or TV show. It uses a Natural Language Processing (NLP) model and a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions. The motivation behind this project is to develop a deeper understanding of recommender systems and create a model that can perform Clustering on comparable material by matching text-based attributes. Specifically, thinking about how Netflix creates algorithms to tailor content based on user interests and behaviour.

## Data Summary:
This dataset consists of tv shows and movies available on Netflix as of 2019.
It is collected from Flixable which is a third-party Netflix search engine.
* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Releaseyear of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description

## Conclusion and Insights:
● It was interesting to ﬁnd that majority of the content available on Netﬂix is Movies.

●	But in recent years it has been focusing more on TV-shows.

●	Most of these contents are released either in the year ending or the beginning.

●	United States and India are among the top 5 countries producing all of the platform’s available content.

●	Also 6 of the actors among the top ten actors with maximum content are from India.

●	TV-MA tops the charts, indicating that mature content is more popular on Netﬂix.

●	k=10 was found to be an optimal value for clusters using which we grouped our data into 10 distinct clusters.

●	Using the given data a simple recommender system was created using  cosine_similarity and recommendations for Movies and TV shows were obtained.
