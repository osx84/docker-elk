# docker-elk

$ cd ~/docker-elk
$ mkdir -p elasticsearch/{config,storage}
$ chown -R 1000:1000 elasticsearch/storage/

# For password protected access to kibana

$ cd ~/docker-elk/nginx/etc
$ htpasswd -c .htpasswd.user admin