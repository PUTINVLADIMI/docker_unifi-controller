# docker_unifi-controller

Controlador Unifi - One Liner

docker run --init -d --restart always --net=host -e PGID=900 -e PUID=900 -v ~/unifi:/unifi --name unifi-controller jacobalberty/unifi:5.8.30-sc
