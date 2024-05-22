Top 100 Trending Hindi Songs Dashboard

Overview
This project aims to analyze and visualize the top 100 trending Hindi songs on Spotify. Using the Spotipy library, data is collected and processed into three distinct dataframes. A Tableau dashboard is then created to provide insights through various charts.

Data Collection
Data is sourced from Spotify using the Spotipy library. The following dataframes are created:
1.	Songs: Contains a list of the top 100 trending Hindi songs.
2.	Artists: Contains a list of artists for each song.
3.	Markets: Contains a list of markets in which each song is available.

Data Structure
The dataframes are connected through the song_id, which serves as the primary key.
•	Songs DataFrame:
o	song_id: Unique identifier for each song.
o	song_name: Name of the song.
o	popularity: Popularity score of the song.
o	duration_ms: Duration of the song in milliseconds.
o	Other relevant song metadata.
•	Artists DataFrame:
o	song_id: Unique identifier for each song.
o	artist_name: Name of the artist.
o	Other relevant artist metadata.
•	Markets DataFrame:
o	song_id: Unique identifier for each song.
o	market: Market where the song is available.
o	Other relevant market metadata.

Tableau Dashboard
The Tableau dashboard consists of three main charts, providing comprehensive insights into the trending Hindi songs:
1.	Top 100 Most Trending Hindi Songs and Their Popularity:
o	Displays the top 100 songs filtered by their duration.
o	Visual representation of the popularity score of each song.
2.	Top 5 Artists with Maximum Hits:
o	Highlights the artists with the most songs in the top 100 list.
o	Comparative analysis of the number of hits by each artist.
3.	Hits by Veteran Indian Singers:
o	Focuses on songs by veteran Indian singers, such as Lata Mangeshkar, that are still trending.
o	Analysis of the enduring popularity of these iconic singers.

Prerequisites
•	Python 3.x
•	Spotipy library
•	Tableau

Usage
1.	Set up Spotify API credentials:
o	Obtain your Spotify API credentials (client ID and client secret) from the Spotify Developer Dashboard.
o	Set your credentials as environment variables or directly in the script.

Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
•	Thanks to Spotify for providing the data through their API.
•	Special thanks to the artists for their incredible music.

Contact
For any questions or feedback, please reach out to arnabm2007@gmail.com
