# docker-cura
Cura 3D in a Docker container, Web UI

```
docker rm cura
docker rmi cura
docker build -t cura .
docker images
docker run --rm -p 5805:5800 --name cura-docker cura
```

Mount /config, /storage and /output as persistent volumes

