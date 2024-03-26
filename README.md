# Unsupervised ML: Clustering Songs


## K Means Clustering


### Case Study
Welcome to Moosic!

Moosic is a little start-up that creates playlists curated by music experts and specialists in old and new trends. Users can subscribe to their website and listen to these playlists through their preferred Music App (be it Spotify, Apple Music, Youtube Music…). They love the fact that their playlists have a personal touch, and that each playlist encapsulates a certain “mood” or “style”.

But business is scaling up fast and the music experts are slow in creating new playlists. They have hired you with a clear mission: use Data Science to add a degree of automatisation to the creation of playlists.

They want you to use a dataset that has been collected from the Spotify API and contains the audio features (tempo, energy, danceability…) for a few thousand songs and use a basic clustering algorithm such as K-Means to divide the dataset into a few clusters (which will become playlists).

Some of the members of the team are skeptical about these audio features being able to capture the actual “mood” of a song: they feel this is something very subjective that only a human can judge. Others are hopeful that a solution that incorporates Data Science can be even better and create connections between songs that might feel unexpected at first glance, but that ultimately make sense.

Either way, in this first iteration of the project they expect you to have an initial prototype. No pressure: the playlists don’t have to be perfect, and the company understands that they are at the beginning of a lengthy process. Between you and the musical experts, a couple of assessments will have to be made:

#### Are Spotify’s audio features able to identify “similar songs”, as defined by humanly detectable criteria? When you listen to two rock ballads, two operas or two drum & bass songs, you identify them as similar songs. Are these similarities detectable using the audio features from Spotify?
#### Is K-Means a good method to create playlists? Would you stick with this algorithm moving forward, or explore other methods to create playlists?
By the end of this project, you are expected to present your clusters to the team and discuss these questions with them.

## project Notebook: Challenege_1

This Python notebook focuses on analyzing a dataset containing information about 10 songs from Spotify. Here's a summary of the main sections and tasks covered:

#### Explore the Dataset:
The notebook begins by importing the 10 songs dataset and exploring its structure using pandas.
Column names are cleaned to remove spaces for ease of access.
#### Analyze Danceability and Liveness:
The top 3 most danceable songs and songs with the highest liveness scores are identified and discussed.
The notebook encourages subjective analysis by asking whether the liveliness and danceability scores align with personal perceptions of the songs.
#### Use KMeans for Clustering:
The KMeans clustering algorithm is applied to the dataset with different configurations:
Varying the number of clusters (e.g., 3, 4).
Experimenting with different random seeds (e.g., None, 0, 42).
Clustering results are examined, and it's noted that the assignment of songs to clusters can change based on the random seed used.
A comparison is made to highlight the impact of changing the random seed on the clustering results.
#### Familiarize with scikit-learn Documentation:
The notebook concludes with a recommendation to familiarize oneself with the scikit-learn documentation, particularly focusing on the KMeans function used in the analysis.
Overall, the notebook provides a hands-on exploration of a small dataset using pandas for data manipulation, scikit-learn for clustering analysis, and encourages subjective interpretation of the results.

![image](https://github.com/lisardo-iniesta/datascience-bootcamp/assets/126266573/26de6cc6-dfc7-4e5d-bc03-3b6b4a23574d)

