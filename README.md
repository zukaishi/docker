# docker

```コンソール
docker run -d -p 80:80 -v /Users/Apple/docker/php70-apache/www:/var/www/html --name php70-apache php:7.0-apache
```

localhost:8080 で、サーバ起動
ローカルの　/Users/Apple/docker/php70-apache/www　を
dockerの　/var/www/html で使用する。
php70-apache　という名前でdockerを起動する
php:7.0-apache　というパッケージを使用する

```ブラウザ
localhost
```

```その他コマンド
docker container stop php70-apache
docker container start php70-apache
docker container rm php70-apache
```