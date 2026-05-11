# music-pioneerpork

[Pioneer Pork (放牧和豚)](https://pioneer-pork.com/)をテーマにしたAI生成楽曲を再生するウェブベースの音楽プレイヤーです。楽曲は[Suno](https://suno.com/)を使用して制作されました。

**再生はこちら:** [**放牧和豚 Music Player**](https://code4fukui.github.io/music-pioneerpork/)

このアプリケーションは、楽曲の再生、アルバムアートの表示、歌詞の閲覧ができるシンプルなインターフェースを提供します。ブラウザ上で直接動作する、自己完結型の静的ウェブページです。

![左側にプレイリスト、中央にアルバムアートとオーディオコントロール、右側に歌詞が表示されている音楽プレイヤーのインターフェース。](https://user-images.githubusercontent.com/1025994/281987823-76953282-581d-4033-9069-7977a4197992.png)

## プレイリストの更新

音声ファイル、画像、プレイリストデータは公開されているSunoのプレイリストからダウンロードされます。アセットをローカルにダウンロードまたは更新するには、Denoを使用して以下のコマンドを実行します。

このプロセスでは、[music-opendata-fukui](https://github.com/code4fukui/music-opendata-fukui)プロジェクトのスクリプトを使用しています。

```sh
deno run -A https://code4fukui.github.io/music-opendata-fukui/download.js 784c5dea-07fb-405b-b47b-b39f38b401ff
```

## 音楽ライセンス

- CC BY [Pioneer Pork](https://pioneer-pork.com/)

## 謝辞

- パイオニアポーク 有方さん (Mr. Arikata from Pioneer Pork)
- オリジナルのSunoプレイリスト: https://suno.com/playlist/784c5dea-07fb-405b-b47b-b39f38b401ff
