# smellysearch

> 🎵 smelly search, smeelllyy search

> where are they looking(for) you! 🎵

```shell
docker build -t smellysearch .

docker run -p 8080:80 smellysearch
```

## For static image,
```shell
docker build -f static/Dockerfile -t boseabhishek/smellysearch:static-0.1.0 .

docker run -p 8081:80 boseabhishek/smellysearch:static-0.1.0
```

## For embebed image,
```shell
docker build -f embed/Dockerfile -t boseabhishek/smellysearch:embed-0.1.0 .

docker run -p 8081:80 boseabhishek/smellysearch:embed-0.1.0
```
