# docker-win10-dokuWiki
Windows10＋RancharDesktop環境でDockerのDokuWikiを構築（Wiki構築）

## 環境
- OS：Windows 10 Pro 21H2
- RancharDesktop：1.7.0

> **Warning**
- bitnaは動かない

## Dockerコマンド
``` bash
# Docker-compose実行
$ docker-compose up -d

# Docker コンテナ確認
$ docker ps

# Docker イメージ確認
$ docker images

# Docker コンテナの中に入る
$ docker exec -it [コンテナID] bash

# dokcer-composeのリビルド
$ docker-compose up -d --build  --force-recreate

```

## ブラウザからURLでDokuWikiに接続
~~~
http://localhost:8080
~~~
![picture 1](images/README/1670203476014.png)  


## 参考
- [docker-composeを利用してDokuWikiを構築する](https://mebee.info/2020/07/04/post-13052/)
- [DokuwikiをDockerで構築](https://qiita.com/tan102422/items/d10ff7a8ba9f4d1fd69b)
