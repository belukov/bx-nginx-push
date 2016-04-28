# bx-nginx-push

This is a prepared nginx config files to use push-sream-module.

Definen some ports and other settings.

Based on bitrix-vm configs

### Install nginx with push-stream-module

http://github.com/wandenberg/nginx-push-stream-module.git

P.S. nice guide for Debian: http://www.lisov.org/dobavlenie-modulya-nginx-debian-way.html (rus)

### Clone me

```
cd /etc/nginx
git clone https://github.com/belukov/bx-nginx-push.git bx
```

### Make symlink to push.conf from conf.d (must be inclided in nginx.conf)
```
cd /etc/nginx/conf.d
ln -s ../bx/push.conf
```

NOTE:
ssl switched off by default. require sertificate

