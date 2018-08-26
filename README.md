# server-configs-nginx

```
docker run --name my-site -v /root/nginx/conf.d:/etc/nginx/conf.d -v /root/nginx/cert:/etc/nginx/cert -p 80:80 -p 443:443 -d nginx
```