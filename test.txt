<?xml version="1.0" encoding="UTF-8"?>
This is a textbook.
It is used to show me how to use the github.
execute: vi /etc/httpd/conf/httpd.conf
modify: DirectoryIndex index.html index.html.var  To  DirectoryIndex index.php index.html index.html.var
modify: ServerName www.example.com:80  To  ServerName localhost:80 , save and exit
DocumentRoot default set to "/var/www/html", solved
