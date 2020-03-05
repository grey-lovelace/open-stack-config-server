# Build and Deploy Localy

```
./gradlew build
docker build -t open-stack-config-server:latest .
docker run -p 8888:8888 open-stack-config-server
```
