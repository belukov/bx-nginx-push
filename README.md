# bx-nginx-push
1. install nginx with push-stream-module
http://github.com/wandenberg/nginx-push-stream-module.git
P.S. nice guide: http://www.lisov.org/dobavlenie-modulya-nginx-debian-way.html (rus)

2. clone me
cd /etc/nginx
git clone https://github.com/belukov/bx-nginx-push.git bx

3. make symlink to push.conf from conf.d (must be inclided in nginx.conf)
cd conf.d
ln -s ../bx/push.conf

NOTE:
ssl switched off by default. require sertificate

