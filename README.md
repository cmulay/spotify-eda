<center><h1>🎶 Spotify Exploratory Data Analysis 🎶</h1></center>

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=cmulay.spotify-eda)

## Purpose

- The music industry is expanding faster than ever before. This market is fast expanding and getting more competitive. Companies must differentiate themselves by offering unique, artist-focused content or by inventing new pricing strategies. 
- Spotify, which was created in 2006, has grown to become the world's most popular streaming network. We shall study singers' song trends using the data provided from this site.
- From there, strategies to increase singers' popularity can be proposed, allowing them to be more competitive and successful in the music industry.

## Understanding the Data
- I'm using the Kaggle dataset '[Spotify Charts](https://www.kaggle.com/datasets/dhruvildave/spotify-charts),' which has a file size of 3.48 GB.
- It has 26,173,514 observations and 9 columns: title, rank, date, artist, url, region, chart, trend, and stream. This dataset provides the top 200 streamed music on Spotify every day between January 1, 2017 and December 31, 2021, as collected using the Spotify API. 
- The information is updated on a daily basis. The original chart may be seen here: https://spotifycharts.com/regional

There are 9 columns in this dataset and their description are as follows.
- <i>title</i>: Title of the song
- <i>rank</i>: Rank from 1 - 200 (1 is the most streamed track that day)
- <i>date</i>: Date of data
- <i>artist</i>: Artist name
- <i>url</i>: URL of the song
- <i>region</i>: Countries around the world
- <i>chart</i>: There are 2 charts top200 or viral50
- <i>trend</i>: The position of that song on the chart compared to yesterday. It has 3 values: MOVE_UP, MOVE_DOWN or SAME_POSITION
- <i>streams</i>: The total number of global streams of that song in one day

## In this Exploratory Data Analysis

- Visualization of Artist Popularity
- Streams by region
- Top200 and Viral50 Songs in India Region
- EDA using Apache Spark
- Exploring Top200 and Viral50 Chart
- Trends in Top200 and Viral50
- Highest, Lowest and the Mean (Avg) ranks of songs

<center><h1> Thankyou 💖 </h1></center>
