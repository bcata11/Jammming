##Intro
Hello! This is my first webb-app with React, part of the Full-Stack Engineer career path from Codecademy!


Jammming is a React web application that enables users to create and add playlists to their Spotify account. It does this by utilizing the Spotify API to connect and authenticate to a user's account, and to search for Tracks, Artists or Albums. The results are then presented in a list where individual tracks can easily be added to or removed from a new playlist. Once the playlist has been assembled, it can be given a name and then saved to the user's Spotify account with the click of a button.

##Features
- Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account.
- Search by Song, Album, or Artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button. The app will request song data about the user's input from the Spotify library.
- Populate Results List — Jammming displays the list of returned tracks from the user's query.
- Add Song to a Custom Playlist — users can add a track to their playlist by selecting a + sign on the right side of the track's display container.
- Remove Song from Custom Playlist — users can remove a track from their playlist by selecting a - sign on the right side of the track's display container.
- Change Playlist Title — users can change the title of their custom playlist.
- Save Playlist to Account — users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.
##Instructions
- Download or clone repo.
- Navigate to the project folder in terminal.
- Run npm install.
- Modify the redirect_uri variable on line 3 of 'src/util/Spotify.js' to the URL where you will be deploying the application.
- Modify line 19 of 'src/util/Spotify.js' so that the third argument of the pushState() object matches the location where your application will be hosted. For example, if you will be accessing your application from your root url such as https://www.xyz.com/, then the third argument should be '/'. If your application will be located in a subfolder such as https://www.xyz.com/jamming/, then the third argument should be set to '/jammming/'.
-Run npm run build in the terminal to create the applications's production build.
-Deploy the production build to your hosting service. Instructions for common deployment scenarios and providers can be found here.