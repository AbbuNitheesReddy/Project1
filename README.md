# Movie Recommendation System
# Objective
Build a movie recommendation system that suggests movies to users based on their preferences and viewing history.
# Data Source
We'll use the YBI Founndation dataset, You can download it from YBI Foundation Website.

A movie recommendation system is an application designed to suggest films to users based on various criteria. These systems can help users discover new movies they are likely to enjoy by analyzing their preferences and behaviors, as well as the preferences and behaviors of similar users. Here's an overview of how movie recommendation systems work:

Types of Recommendation Systems

Content-Based Filtering:
Description: This approach recommends movies based on the features of the movies and the user’s past interactions. It focuses on the similarity between items.
Example: If a user likes action movies, the system recommends other action movies.
How it works: It analyzes movie attributes such as genre, director, actors, and plot keywords. It matches these attributes with the user’s preferences or the attributes of movies the user has rated highly.

Collaborative Filtering:
Description: This approach recommends movies based on the behavior of similar users. It focuses on the relationship between users and items.
Example: If user A and user B have similar taste in movies, and user A likes a movie that user B hasn't seen yet, that movie might be recommended to user B.

Types:
User-based Collaborative Filtering: Finds users similar to the target user and recommends movies they liked.
Item-based Collaborative Filtering: Finds movies similar to ones the user has liked and recommends those.

Hybrid Methods:
Description: These methods combine content-based and collaborative filtering approaches to leverage the strengths of both.
Example: A system might use collaborative filtering to identify a set of movies and then use content-based filtering to refine these recommendations based on the user's past preferences.
