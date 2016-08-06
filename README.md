# Docker Compose サンプル

## 概観



## 初期設定

ホストにマウントしたディレクトリの所有者が `root` になってしまって、 `fluentd` が目的のログファイルをテイルできない。

```
[client] $ docker-machine ssh <host>
[host] $ sudo chown -R docker:1000 /var/log/fluentd/
[host] $ sudo chown -R docker:1000 /var/log/nginx/
```

## 起動

```
$ docker-compose up -d
```

![https://gyazo.com/c0cfbdad1b2c6bd1eb2d9366e7640221](https://i.gyazo.com/c0cfbdad1b2c6bd1eb2d9366e7640221.png)

![https://gyazo.com/383b10b28d04c205c4c40cfc4ab4375c](https://i.gyazo.com/383b10b28d04c205c4c40cfc4ab4375c.png)
