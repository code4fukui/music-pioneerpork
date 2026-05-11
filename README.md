# music-pioneerpork

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web-based music player featuring AI-generated songs about [Pioneer Pork (放牧和豚)](https://pioneer-pork.com/). The music was created using [Suno](https://suno.com/).

**Listen here:** [**放牧和豚 Music Player**](https://code4fukui.github.io/music-pioneerpork/)

The application provides a simple interface to play the songs, view album art, and read the lyrics. It is a self-contained static web page that runs directly in your browser.


![Music player interface showing a playlist on the left, album art and audio controls in the center, and lyrics on the right.](https://user-images.githubusercontent.com/1025994/281987823-76953282-581d-4033-9069-7977a4197992.png)


## Updating the Playlist

The audio files, images, and playlist data are downloaded from a public Suno playlist. To update or download the assets locally, run the following command using Deno.

This process utilizes a script from the [music-opendata-fukui](https://github.com/code4fukui/music-opendata-fukui) project.

```sh
deno run -A https://code4fukui.github.io/music-opendata-fukui/download.js 784c5dea-07fb-405b-b47b-b39f38b401ff
```

## Special Thanks

- パイオニアポーク 有方さん (Mr. Arikata from Pioneer Pork)
- Original Suno Playlist: https://suno.com/playlist/784c5dea-07fb-405b-b47b-b39f38b401ff
