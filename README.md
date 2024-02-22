# Musical-Evolution
This was a school project investigating how the composition of popular music has changed over the past decades, and which aspects of a song are most important to popularity.

# Note: I will not be providing code to this due to university restrictions. 

# Dataset Information
For this project, we utilized a dataset from Kaggle which contained music information from the Spotify Web API. We investigated the popularity of any given song, along with the decade it came out, and its (spotify-assigned) levels of danceability, energy, loudness, and so on. 

# Exploratory Data Analysis
We decided to take a peek under the hood of our data, and get a better sense of what exactly we would be analyzing. We found that there was a huge variability in how long audio tracks were in the dataset, due to very short ringtones, or very long podcasts. We weren't interested in measuring the popularity of these, as they weren't songs, so we removed the most significant outliers. We also discovered that we had made an incorrect assumption regarding how Spotify calculated the popularity of songs. We found that not just the total number of listens a song had, but how recent they were was taken into consideration when determing popularity. As such, we subsetted our data to only include songs from 2021, rather than several decades. We ensured the independence of our chosen variables, and continued with our in-depth analysis. 

# In-Depth Analysis
[Will come back to later]

# Results
We found that for songs from 2021, the variables with the highest positive correlation to popularity were the loudness and energy of a song. On the flip side, acousticness and instrumentalness had the largest negative correlation with the popularity of a song. We also identified some key areas of music that have gradually changed over time. Since the 1920s, the average energy of music has tripled. In addition, the percantage of explicit songs has gone from 2% in the 1990s, to 15% in the 2020s. Finally, we found that the key, time signature, liveliness and danceability of music has remained relatively constant throughout the decades.
