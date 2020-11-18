# Nginx

## crt AND key

- 用于本地`https`转发
- 放在`/usr/local/etc/nginx`目录下

## use

```shell
cd /usr/local/etc/nginx
sudo vim nginx.conf
# add: include ~/.dotfiles/nginx/servers/*;
```