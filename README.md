# 【gin + gorm】劣化版ツイッターアプリ GAE,Cloudsql デプロイ用
GAEとCloud SQLの設定をしてから実行して下さい。

```
go run main.go
```

## 注意事項
動かす前に、.envファイル内にCloud SQLで定めた設定を記述して下さい。

```
mytweet_CONNECTIONNAME=project-id:region-name:instance-name
mytweet_USER=username
mytweet_PASS=password
mytweet_DBNAME=test
```