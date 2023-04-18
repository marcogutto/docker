# docker

### Comandos básicos

#### Help
```
docker logs --help
```

#### Run
```
docker run --name some-mongo -p 27017:27017 -d mongo:5.0.8-focal
```

#### PS
```
docker ps
```

#### Images
```
docker images
```

#### Search
```
docker search mongo
```

#### Exec
```
docker exec -it 3f86500a4ebb bash
```

#### Tag
```
docker tag mongo:5.0.8-focal mongo:minhaTag
```

#### Build
```
docker build -t marcogutto/mongo:minhaTag -f Dockerfile .

docker build -t marcogutto/mongo:minhaTag .
```

#### Login
```
docker login -u meuLogin -p minhaSenha
docker login -u meuLogin -p minhaSenha docker-registry.meudominio.com.br
```

#### Push
```
docker push marcogutto/mongo:minhaTag
```