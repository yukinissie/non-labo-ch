# non-labo-ch

のんラボ用の環境プロジェクトです。

youtubeチャンネルはこちら [https://www.youtube.com/channel/UCzpY7GBbWJFHA3JVjkgbAjA](https://www.youtube.com/channel/UCzpY7GBbWJFHA3JVjkgbAjA)

ブログで内容を見るにはこちら [https://labo.nozomi.bike/?q=%E3%81%AE%E3%82%93%E3%83%A9%E3%83%9C](https://labo.nozomi.bike/?q=%E3%81%AE%E3%82%93%E3%83%A9%E3%83%9C)

## 環境

|-|-|
|---|---|
|Nginx|1.19系|
|PHP|7.4系|
|MySQL|8.0系|
|Composer|1.10系|
|Node|latest|

### VSCode 設定

[https://gist.github.com/nonz250/4a92b6c75318411080c24c8c740f9bef](https://gist.github.com/nonz250/4a92b6c75318411080c24c8c740f9bef)

VSCodeの設定が面倒な方は私の設定を公開しておきますのでこれをダウンロードして使ってみてください。

詳しくはこちらの記事を読むといいかもしれません。VSCodeの設定が自分でできる方はその環境を利用しても大丈夫です。

[https://labo.nozomi.bike/article/83](https://labo.nozomi.bike/article/83)

## コマンド

### 初めてこのリポジトリを使う場合

```shell script
cp docker-compose.yml.example docker-compose.yml
```

### 起動

```bash
docker-compose up -d
```

### 停止

```bash
docker-compose down
```
