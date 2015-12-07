# docker-syncthing-discovery
Syncthing discovery docker container
You need to specify cert.pem and key.pem:
docker run -d --name syncthing-discovery -p 443:8443 -v /path/to/ssl/:/ssl/ bn0ir/docker-syncthing-discovery
