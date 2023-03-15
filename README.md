# SpotMyBackup

Backup and Restore your Spotify Playlists and "My Music".

This javascript based app allows you to backup all your playlists and import them in any other Spotify Account. It uses the OAuth-Functionality of Spotify to be able to handle your personal playlists.

In consequence, no credentials or data is stored or processed on the Webserver itself.

Improvements:

* Loaded in the correct order (already implemented)
* Playlist description and public status
* Playlist image


You should define a js file with the following structure and put it in the local/ file:

```js
config = {
    "uri": "http://localhost:8888",
    "redirect_uri": "http://localhost:8888/login.html",
    "client_id": "[Your Code]",
    "slowdown_import": 100,
    "slowdown_export": 100
};
```
