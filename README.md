# docker-training

To build: 
```
docker build -t html_static_image .
```

To run locally:
```
docker container run --detach -p 80:80 html_static_image
```

To confirm running on port:
```
curl localhost:80
```
