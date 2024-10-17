# 1. Firewall
## 2. iptables
*in nghiêng*

**bôi đậm**



![alt](Screenshot%202024-10-17%20at%2021.41.44.png)


file config /etc/nginx.conf

```sh
location / {
        # First attempt to serve request as file, then
        # as directory, then fall back to displaying a 404.
        try_files $uri $uri/ =404;
    # proxy_pass http://localhost:8080;
    # proxy_http_version 1.1;
    # proxy_set_header Upgrade $http_upgrade;
    # proxy_set_header Connection 'upgrade';
    # proxy_set_header Host $host;
    # proxy_cache_bypass $http_upgrade;
}
```
