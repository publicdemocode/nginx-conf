# nginx-conf

/etc/nginx/nginx.conf

/etc/nginx/sites-available/default

nginx.app24.click 139.162.204.193

docker run -d --name apache2 -p 8080:80 httpd:2.4

apt-get update
apt-get install -y python3 python3-pip
pip3 install certbot certbot-ngin

certbot --nginx -d nginx.app24.click --non-interactive --agree-tos --register-unsafely-without-email
certbot --nginx -d demo2.app24.click --non-interactive --agree-tos --register-unsafely-without-email