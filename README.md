# docker-training

To build: 
```
docker build -t html_static_image .
```

Run:
```
docker container run --detach -p 80:80 html_static_image
```

To confirm build, run:
```
curl localhost:80
```
