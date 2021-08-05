# About

Mostly a playground for Docker. Right now the container runs a static webapp.

# How to run

1. `docker build -t foo . && docker run --publish 8000:8000 -it foo`
2. See app in `localhost:8000`
