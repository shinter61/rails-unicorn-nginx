## 概要
docker + nginx + unicorn + rails で環境構築したリポジトリ

## 起動
カレントディレクトリは /unicorn_practice とする

1. docker-compose up

2. docker exec -it rails bundle exec rails db:create

3. http://127.0.0.1
