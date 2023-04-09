# コンテナハンズオン
超簡易的なWebサイトをコンテナで立ち上げることを目的とする。

## 事前準備
- Docker Desktopのインストール
    - インストーラーは以下よりダウンロード可能。
    - https://www.docker.com/products/docker-desktop/


## 利用技術
- HTML
- CSS
- JavaScript

## 利用方法
1. コンテナの起動&動作確認
``` 
docker-compose up -d
curl http://localhost:8080
```

2. コンテナの確認
```
docker ps
```

3. コンテナイメージの確認
```
docker images
```

4. 以下のコマンドでコンテナを削除する。
```
docker-compose down
```

## 補足
コンテナのイメージファイルだけを作成したい場合
```
docker-compose build
```