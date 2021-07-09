## Server Installieren

```
sudo apt-get update
sudo apt-get install nginx graphviz aspell ghostscript clamav git mlocate

```

## Mysql Server

```
sudo apt-get install mysql-server mysql-client

```

## PHP

```
sudo apt-get install php-fpm php-cli
```

## PHP Module

```
sudo apt-get install php-mysql php-mbstring php-xmlrpc php-zip php-gd php-xml php-bcmath php-ldap php-pspell php-curl php-intl php-soap

```

## php.ini ändern

```
nano /etc/nginx/sites-available/default

server {
        listen 8081 default_server;
        listen [::]:8081 default_server;
        root /var/www/html/moodle;
        index index.php index.html index.htm index.nginx-debian.html;
        server_name _;
        location / {
                try_files $uri $uri/ =404;
        }
        location ~ [^/]\.php(/|$) {
                fastcgi_split_path_info  ^(.+\.php)(/.+)$;
                fastcgi_index            index.php;
                fastcgi_pass unix:/var/run/php/php-fpm.sock;
                include fastcgi_params;
                fastcgi_param   PATH_INFO  $fastcgi_path_info;
                fastcgi_param   SCRIPT_FILENAME $document_root$fastcgi_script_name;
}
}
```