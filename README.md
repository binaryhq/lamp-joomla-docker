# lamp-joomla-docker
```
docker build -t ubuntu-wordpress https://github.com/ningappa/ubuntu-trusty-wordpress.git
```
```
docker run -d --name 7thstreet \
  -e VIRTUAL_HOST=www.7thstreet.xyz  \
  -e VIRTUAL_DOMAIN=www.7thstreet.xyz \
  -e MYSQL_USER=mydbuser \
  -e MYSQL_PASS=mydbpassword \
  -e MYSQL_DBNAME=mydbname \
  -e WP_USER=admin123 \
  -e WP_PASS=pass1233 \
  -e USER_EMAIL=ningappa@poweruphosting.com  \
  -e FILEMANAGERUSER=filemgr \
  -e FILEMANAGERPASSWORD=filepassword \
  ubuntu-joomla
```
