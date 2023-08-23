# _NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING

![images (1) (1) (1)](https://github.com/NamiraMujawar/_NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING/assets/120715329/74b111c8-4a14-4755-a227-2d4809159911)






Netflix is a groundbreaking American subscription video on-demand streaming service, offering an extensive array of films and TV series produced by its own media company. It has a global presence, reaching audiences in multiple languages, redefining entertainment consumption and becoming an integral part of modern culture.

#**Problem Statement**
---
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

#**Dataset Information**
---
The dataset contains a total of 7,787 rows and 12 columns. Here is the information about each column:

**show_id:** Unique identifier for each show/movie.

**type:** Indicates whether it is a "Movie" or "TV Show."

**title:** Title of the show/movie.

**director:** Name of the director (may contain missing values).

**cast:** Cast members of the show/movie (may contain missing values).

**country:** Country where the show/movie was produced (may contain missing values).

**date_added:** Date when the show/movie was added to Netflix (may contain missing values).

**release_year:** Year of release for the show/movie.

**rating:** Content rating for the show/movie (may contain missing values).

**duration:** Duration of the show/movie.

**listed_in:** Categories or genres the show/movie falls under.

**description:** Brief description of the show/movie.

The dataset has a mixture of data types - one integer column (release_year) and eleven object columns (strings). Some columns have missing values, such as director, cast, country, date_added, and rating. The memory usage for this dataset is approximately 730.2 KB.


![Screenshot (98)](https://github.com/NamiraMujawar/_NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING/assets/120715329/eeae5c40-a73b-4ffa-a9f0-b117d4848e80)



#**Project Summary -**
---
This project analyzed Netflix's content dataset of TV shows and movies from 2019. It revealed a diverse content range, with more movies than TV shows. TV-MA was the preferred TV show rating, and content additions peaked from October to January. Documentaries, Standup Comedy, and Drama were prominent genres, and Kids TV stood out for TV shows. The K Means algorithm identified 29 optimal content clusters. The United States had the most content, and India emerged as a significant source. Approximately 30% of movies were Netflix originals. These insights can guide content curation and enhance understanding of audience preferences, enabling Netflix to provide a diverse and engaging viewing experience for its global users.

#**Conclusion**
---

* Active content additions occur from October to January, indicating a seasonal pattern.

* Top genres: Documentaries, Standup Comedy, Drama, and International Movies.

* Emphasis on Kids TV for TV shows.

* Movies range from 50 to 150 minutes in duration.

* Many single-season TV shows, including limited-series content.

* NC-17 movies are longest, TV-Y rated movies shortest.

* US and India have the most content, with India being significant for movies.

* Around 30% of movies are originals, 70% acquired from other channels.

* Netflix hosts 5372 movies and 2398 TV shows, more focus on movies.

* TV-MA ratings dominate TV shows.



