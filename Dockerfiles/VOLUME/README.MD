### Default storage path for every container
/var/lib/overlay2/
### Docker Vloumes path
/var/lib/docker/volumes
### syntax to create a docker Volumer
docker volume create <volume name>
### Starting a docker container with volume
docker run -d -v <volume name (or) data path>:/usr/share/nginx/html -p 80:80 nginx