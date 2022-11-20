## サービス開始  

compose.ymlがあるディレクトリ内で下記コマンド

```
docker-compose up -d --build
```

- ブラウザでhttp:// localhost: 8888/にアクセス する。

## サービス停止  

```
docker-compose down
```

サービス停止してもimageは残る。

## 再開  
次回サービス開始時もdocker-compose up -d --buildで素早く立ち上がる。  
作成したファイルはローカルのnotebookフォルダ内に格納されている。