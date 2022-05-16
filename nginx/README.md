# Nginx

## CRT

- 用于本地`https`转发
- 放在`/usr/local/etc/nginx`目录下

## 配置

```shell
cd /usr/local/etc/nginx

sudo vim nginx.conf

# 在里面添加
include /Users/wrz/.dotfiles/nginx/servers/*;
```
