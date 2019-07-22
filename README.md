# mov-to-gif
QuickTimeで録画した.movファイルをGithubに貼れる.gifに変換するコマンド（備忘

# init
インストール
```
brew install ffmpeg
```

# 手順
1. QuickTime起動
2. 画面録画（録画ストップはCommand+Control+esc)
3. 保存
4. 変換！（下記）
5. githubに貼り付け

```
$ ./mov-to-gif.sh {保存したmovファイル名} {変換するgifファイル名}
```
