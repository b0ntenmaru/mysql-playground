## コンテナ起動
`docker-compose up`

## 初期データを投入
`mysql -h 0.0.0.0 -u docker -P 3306 -p sample_db < mysql_study.backup`