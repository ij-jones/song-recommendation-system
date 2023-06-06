# Song Recommendation System

## Features
* Fetches user data from the Spotify API, including listening history and preferences.
* Analyzes user preferences and listening patterns to generate personalized song recommendations.
* Provides a user-friendly command-line interface for interacting with the system.
* Allows users to explore recommended songs and add them to their playlists directly within the application.

## Prerequisites
To run this application, you need to have the following:

* Python 3.x installed on your machine.
* A Spotify developer account and API credentials. You can create an application and obtain the necessary credentials from the **Spotify Developer Dashboard**.
* The spotipy Python library, which can be installed via ```pip``` using the command:
~~~~ 
pip install spotipy
~~~~

## Installation
* Clone this repository to your local machine or download the source code as a ZIP file.
~~~~ 
git clone https://github.com/ij-jones/song-recommendation-system.git
~~~~
* Navigate to the project directory.
~~~~
cd song-recommendation-system
~~~~

## Configuration
Before running the application, you need to provide your Spotify API credentials. Open the ```config.py``` file and update the following variables:
~~~~
CLIENT_ID = 'your_client_id'
CLIENT_SECRET = 'your_client_secret'
REDIRECT_URI = 'your_redirect_uri'
~~~~
Replace ```'your_client_id'```, ```'your_client_secret'```, and ```'your_redirect_uri'``` with your actual Spotify API credentials. Save the file after making the changes.

## Credits
This Song Recommendation System was developed by Isaiah Jones.

## Disclaimer
Please note that the Song Recommendation System uses the Spotify API and relies on its data. The quality and availability of recommendations may vary based on the data provided by the Spotify API and the user's listening history. The system does not guarantee the accuracy or suitability of the recommendations.
