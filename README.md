# docker

```
watch "docker ps"

docker history nginx
docker pull nginx
docker rm nginx

docker pull nginx
docker run --name nginx -p 80:80 nginx

docker rm 2e251f6de16936a298b82e3cd364e91727127c99f6f60e98897edd39c9e6a8e5


```

```コンソール
docker run -d -p 80:80 -v /Users/Apple/docker/php70-apache/www:/var/www/html
--name php70-apache php:7.0-apache
```
<br>
localhost:8080 で、サーバ起動 <br>
ローカルの　/Users/Apple/docker/php70-apache/www　を<br>
dockerの　/var/www/html で使用する。<br>
php70-apache　という名前でdockerを起動する<br>
php:7.0-apache　というパッケージを使用する<br>

```ブラウザ
localhost
```

```その他コマンド
docker container stop php70-apache
docker container start php70-apache
docker container rm php70-apache
```

