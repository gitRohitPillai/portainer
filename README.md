# portainer
Portainer Community Edition Basics

# Portainer CE Installation for Docker Standalone


`docker volume create portainer_data`

`docker run -d -p 9000:9000 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest`

vulhub/django:4.0.5

nginx:stable-alpine

# If codespace stops

1. Start the codespace again
2. Give command to start the portainer container - docker start portainer
3. wpstack


