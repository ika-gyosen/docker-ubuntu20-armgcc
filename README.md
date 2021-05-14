# 使い方
```./src``` 以下にMakefileのあるソースコードを配置すると、自動的にarmコンテナの中へファイルが同期されます。  
armコンテナのセットアップが完了し、ファイルを配置したら
```
docker-compose run
```
すると、makeが走ります。
# SETUP
```
docker-compose up -d
```