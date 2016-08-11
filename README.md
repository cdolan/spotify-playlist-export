# spotify-playlist-export

Easy copy/paste song export from Spotify.

## Requirements
  - [jq](https://stedolan.github.io/jq/)

## Usage

Select the songs you want to export and use **Edit > Copy** in the menu. Then
run the following command to retrieve the artist and song name:

### OS X

```
pbpaste | spotify-playlist-export
```

### Linux

```
xclip -o | spotify-playlist-export
```

## License

ISC License
