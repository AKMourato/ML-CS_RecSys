# ML Case study: Movie recommendation systems

Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user.
Recommender systems try to capture the patterns and similar behaviors of people, to help predict what else a certain people might enjoy.
They are are utilized in a variety of areas and are most commonly recognized as playlist generators for video and music services like Netflix, YouTube and Spotify, product recommenders for services such as Amazon, or content recommenders for social media platforms such as Facebook and Twitter or Instagram.

In this case study is built a movie recommendation system using Content-Based Filtering.
A Content-based recommendation system tries to recommend items to users based on their profile.
The user's profile revolves around that user's preferences and tastes.
It is shaped based on user ratings, including the number of times that user has clicked on
different items or perhaps even liked those items.
The recommendation process is based on the similarity between those items.
Similarity or closeness of items is measured based on the similarity in the content of those items.

### Advantages and Disadvantages of Content-Based Filtering

##### Advantages

-   Learns user's preferences
-   Highly personalized for the user

##### Disadvantages

-   Doesn't take into account what others think of the item, so low quality item recommendations might happen
-   Extracting data is not always intuitive
-   Determining what characteristics of the item the user dislikes or likes is not always obvious

### Advantages and Disadvantages of Collaborative Filtering

##### Advantages

-   Takes other user's ratings into consideration
-   Doesn't need to study or extract information from the recommended item
-   Adapts to the user's interests which might change over time

##### Disadvantages

-   Approximation function can be slow
-   There might be a low of amount of users to approximate
-   Privacy issues when trying to learn the user's preferences

<p align="center">
  <img src="https://github.com/MKSK22/CS-ML-RecSys-ContBased/blob/main/RecSys.png?raw=true"/>
</p>

