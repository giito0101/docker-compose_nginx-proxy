# docker-compose_nginx-proxy
docker-composeでリバースプロキシサーバを立ち上げドメインアクセス

### docker ネットワークの作成
docker network create --driver bridge shared

### docker-compose 起動
docker-compose up -d
