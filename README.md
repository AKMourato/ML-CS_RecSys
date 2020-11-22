# ML Case study: Movie recommendation systems

Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user.
Recommender systems try to capture the patterns and similar behaviors of people, to help predict what else a certain people might enjoy.
They are are utilized in a variety of areas and are most commonly recognized as playlist generators for video and music services like Netflix, YouTube and Spotify, product recommenders for services such as Amazon, or content recommenders for social media platforms such as Facebook and Twitter or Instagram.

In this case study is built two movie recommendation system using two type of approaches: **Content-Based Filtering** and **Collaborative Filtering**

A Content-based recommendation system tries to recommend items to users based on their profile.The user's profile revolves around that user's preferences and tastes.It is shaped based on user ratings, including the number of times that user has clicked on different items or perhaps even liked those items.The recommendation process is based on the similarity between those items.
Similarity or closeness of items is measured based on the similarity in the content of those items.

Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future, and that they will like similar kinds of items as they liked in the past. The system generates recommendations using only information about rating profiles for different users or items. By locating peer users/items with a rating history similar to the current user or item, they generate recommendations using this neighborhood. Collaborative filtering has basically two approaches: **user-based** and **item-based**.
User-based collaborative filtering is based on the user similarity or neighborhood.
Item-based collaborative filtering is based on similarity among items.

**Note**: Don't confuse item-based collaborative filtering with content-Based Filtering. The point of content-based filtering is that we have to know the content of both user and item.The item-based recommendation is totally based on user-item ranking (e.g., a user rated a movie with 3 stars, or a user "likes" a video). When you compute the similarity between items, you are not supposed to know anything other than all users' history of ratings. So the similarity between items is computed based on the ratings instead of the meta data of item content.


<p align="center">
  <img src="https://github.com/MKSK22/CS-ML-RecSys-ContBased/blob/main/RecSys.png?raw=true"/>
</p>


### Content-Based Filtering

##### Advantages

-   Learns user's preferences
-   Highly personalized for the user

##### Disadvantages

-   Doesn't take into account what others think of the item, so low quality item recommendations might happen
-   Extracting data is not always intuitive
-   Determining what characteristics of the item the user dislikes or likes is not always obvious



### Collaborative Filtering

##### Advantages

-   Takes other user's ratings into consideration
-   Doesn't need to study or extract information from the recommended item
-   Adapts to the user's interests which might change over time

##### Disadvantages

-   Approximation function can be slow
-   There might be a low of amount of users to approximate
-   Privacy issues when trying to learn the user's preferences


