####证书生成
> openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /home/www/openssl/nginx.key -out /home/www/openssl/nginx.crt