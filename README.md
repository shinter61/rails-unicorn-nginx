## 概要
docker + nginx + unicorn + rails で環境構築したリポジトリ

## 起動
カレントディレクトリは /unicorn_practice とする

1. docker-compose up

2. db_developmentが無いとエラーを吐くので手動で作る
docker exec -it mysql mysql -u root -p
password
create database db_development;

3. docker-compose down

4. docker-compose up

5. http://127.0.0.1