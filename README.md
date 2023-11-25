
Nginx HTTP Proxy with Let's Encrypt (Certbot) built-in.

Make sure to edit the ${DOMAIN} part of the `nginx/nginx.conf` to set up your own domain.

Example:
```
(...)

server {
  server_name mydomain.com;
  access_log /dev/stdout main;
   underscores_in_headers on;

(...)
```