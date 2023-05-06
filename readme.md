# Build and Run
```
docker-compose build --progress=plain

docker-compose up -d

docker-compose logs -f
```

# wildfly
```
google-chrome --incognito http://localhost:8081/sample/hello
```

# tomcat
```
google-chrome --incognito http://localhost:8082/sample/hello
```

# websphere
```
google-chrome --incognito http://localhost:8083/sample/hello
```

# Stop
```
docker-compose down
```