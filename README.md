## 初期設定
* .env.local → copy → .env にしてください
* .env の項目を任意に書き換えてください

## 軽い説明
mysqlがdocker上で起動するようになります  
user や password は `.env` で指定することになるので任意のものに書き換えてください  
`mysql/mysql_init/*.sql` は最初に実行されます 確認後、必要なければコメントアウトをしてください 

## 実行
```bash
# バックグラウンドで実行
$ docker-compose up -d
```
