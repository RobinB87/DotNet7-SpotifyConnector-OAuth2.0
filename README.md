# SpotifyConnector

Small app which shows some playlists and can upload tracks.

# Techniques

* DotNet 7
* React 18

# Authention
The app uses Spotify’s OAuth 2.0 Authorization Code Flow. If no access token is present in the session, the user is redirected to Spotify’s login page. After successful authentication, Spotify redirects the user back to the app, where the authorization code is exchanged for an access token.


