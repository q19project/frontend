# 开发服务器管理

## 1. 服务器应用安装

```text
yum install nginx
```

## 2. 修改默认主页

```text
vim /etc/nginx/nginx.conf
```

## 3. https配置

```text
        listen 443 ssl;
        ssl_certificate      /etc/nginx/conf.d/SOMEDOMAIN.crt;
        ssl_certificate_key  /etc/nginx/conf.d/SOMEDOMAIN.key;

        ssl_session_cache    shared:SSL:1m;
        ssl_session_timeout  5m;

        ssl_ciphers  HIGH:!aNULL:!MD5;
        ssl_prefer_server_ciphers  on;
```

