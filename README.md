# Nginx Configuration for WordPress and PHP7

Clone into `/etc/nginx/`.

```
sudo rm /etx/nginx/sites-enabled/default
sudo ln -s /etc/nginx/sites-available/wordpress-site /etc/nginx/sites-enabled/wordpress-site
sudo service nginx restart
```