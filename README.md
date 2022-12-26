# Anime-Recommendation-System-Deep-Learning-

The Goals and Objectives of this project are:
1.	To understand the Anime data and finding similar animes.
2.	Analyze Anime data to find similar users who watch anime.
3.	To predict and recommend Animes for a random user.

To begin with, we will investigate the ratings of anime rated by various users. By exploring myanimelib data, we will describe the current state of recommendations and examine potential factors influencing the recommendations. In addition, there are many factors that affect the recommendation to the users such as duplicate ratings, unique genres, volume of users rating a particular genre. A clear relationship between each factor and injury severity will be displayed when we analyze the data for each factor.
	We have used collaborative filtering to examine the relevant user’s behavior, eliminating the need for completely understanding the anime. By applying the user base collaborative filtering we are looking for similar patterns in anime recommendations using the target user and we have also analyzed similar anime that target users have watched and rated using item based collaborative filtering.
By extension, we will develop models to recommend the users to watch anime based upon history of watchlist and genre. We will predict and recommend the users for Anime, we will develop 2 recommendation models: “K means”, “Deep Neural Networks” (Using Tensorflow and Keras). Each model will be tuned to get its peak performance. The model’s performance will be evaluated based on its ‘mean absolute error’, ‘validation loss’, ‘training loss’, ‘cluster sum of squares’. Each model will be trained using the 2022 myanimelib dataset and the same users will be used to recommend for the validation of the model.

The first dataset, "Anime List", provides information on users, Animes they have watched and the ratings; The second data set is “Anime Synopsis data”; which contains more details about Anime like the average score, genre and the synopsis of the titles; The third data set is ‘Anime productions data’ ; which contains information about the type of anime, number of episodes, ranking, popularity, production house and information about the different scores. For the verification of recommendation models, we used data from August 2022.
