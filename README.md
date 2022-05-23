# Learning to work with docker

### Рow to launch this app:

- build image:
```
docker build -t fastapi_image .
```

- run container:
```
docker run -d --name fastapi_container -p 80:80 fastapi_image
```

- send get request at http://127.0.0.1:80
- find:
```
{"message": "Hello World"}
```

- Success!
