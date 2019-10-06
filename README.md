# DockerでMySQL

## 必要なもの

- Docker
- docker compose
- mysql client

## 使用までの手順

### clone

```
git clone git@github.com:phyten/docker_mysql.git
```

### 起動

```
docker-compose -d up
```

### 停止

```
docker-compose down
```

## Clientからのアクセス

```
mysql -h 127.0.0.1 -uroot
```

*※localhostではなく、127.0.0.1を指定。*

## phpmyadmin

```
http://localhost:8080/
```

## 中身をリセットしたい場合

`/docker/db/data` を丸ごと削除
