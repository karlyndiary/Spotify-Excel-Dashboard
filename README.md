# Spotify Excel Dashboard
The dashboard is created using the data from Kaggle, [Spotify - All Time Top 2000s Mega Dataset](https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset). The dataset contains 15 columns and 1994 songs. 

By simply clicking a button, you can effortlessly switch from the Spotify dashboard to the artist dashboard. Once in the artist dashboard, the slicer tool allows you to easily toggle between different artists, providing a focused view of one artist's analysis at a time. This seamless transition between the two dashboards empowers you with a comprehensive overview of all of Spotify's song analysis, as well as in-depth insights into individual artists' analytics, all with just a click of a button. 

## Artist Overview
The Artist Overview of the Dashboard is currently filtered or sliced to focus on ABBA, a popular Swedish music group. This selection allows for a detailed analysis and visual representation of ABBA's performance, statistics, and other relevant information within the dashboard.

We have the stats of ABBA: 
- Total no of releases each year - The group has been consistently releasing music for the past 20 years, with the highest number of releases occurring in 1979.
- Popular Songs - The well-known songs by ABBA, comprising their top 5 hits.
- Popular Genre - As mentioned, ABBA is a popular Swedish music group, their music leans towards Europop.
- Energy Levels - The analysis of ABBA's music indicates that they tend to create calming melodies with lower values for loudness and liveness. However, there is a noticeable spike in the average number of beats per minute, suggesting an upbeat tempo in their songs. The graph also reveals that their music falls within the range of 0 to 50 for acoustics, which implies that electric guitars, keyboards, and synthesizers may be prominent instruments in their compositions. Energy and danceability are relatively lower on the spectrum, indicating a unique blend of musical characteristics in ABBA's music.
- Average Valence throughout the years - The years 1979 and 1980 saw a relatively lower number of releases compared to other years, while 1981 stood out as a particularly prolific year with a whopping 80 music releases, showcasing a peak in the group's creative output and joyous musical compositions.

### We also have metrics such as 
- Unique no of tracks - As we can see, ABBA has 22 unique tracks.
- Popularity - ABBA is quite popular with a score of 53.9.

![Artist Dashboard](https://user-images.githubusercontent.com/116041695/233257040-46d8a395-43ff-48f8-a872-aa0448a0f103.png)

## Spotify Overview
The Spotify Overview of the Dashboard is currently not filtered or sliced. This allows for a detailed analysis and visual representation of the entire dataset's statistics, and other relevant information within the dashboard.

We have the stats of all 1994 songs from the dataset:
- Total no of releases each year - The line graph shows a consistent and gradual increase in the number of songs released since 1960 when only one song was released. The trend continues to rise, reaching its highest point in 1967 with 37 releases, which is the largest number of releases in the dataset for that period. The dataset records the highest number of releases in 2008, with 54 songs, indicating a substantial growth in music production over the years.
- Popular Songs - The bar chart displays the top 5 songs, ranked in order of popularity. Interestingly, there are multiple artists with songs of the same title, but each song is completely different. Among these songs, "Feeling Good" by Nina Simone is the most popular, while "One" by Johnny Cash is the least popular among the top 5.
- Popular Genre - The doughnut chart depicts the top 5 most popular music genres. Album Rock and Alternative Rock occupy the first and third positions, respectively. Adult Standards, Alternative Metal, and Dance Pop follow, with Dance Pop notably securing the fourth spot. It is interesting to observe that rock and metal genres played a significant role in the past, considering the prominence of the two rock genres in the top positions.
- Energy Levels - It is quite interesting that the analysis shows us that average danceability was very low
- Average Valence throughout the years - The analysis of music valence across different years revealed interesting trends. Specifically, the year 1960 had the lowest valence score compared to other years, indicating a less positive or "happy" sound or music in the tracks. On the other hand, the year 1962 had the next immediate highest valence score, suggesting a more upbeat sound. Another notable finding was the dip in valence scores in the year 1994, which returned to a level comparable to 1960. 
- Popular Artists based on Popularity score - The graph illustrates the top 10 artists ranked by their popularity score. The Beatles claim the first position with a popularity score of 2451, while Fleetwood Mac holds the other end of the spectrum with a score of 1083.

### We also have metrics such as 
- Unique no of Artists - There are 731 different artists included in the dataset
- Unique no of tracks - The dataset contains a total of 1994 songs.
- Longest Song - An intriguing find in the dataset is the song "Echoes" by Pink Floyd, which stands out as the longest track at 23 minutes and 53 seconds, significantly surpassing the typical song durations of 2:30 to 3:30 minutes or sometimes even 4 or 5 minutes.

![Spotify Dashboard](https://user-images.githubusercontent.com/116041695/233257024-8e571769-ecb7-4e74-9bab-d3ffab16c7e5.png)
