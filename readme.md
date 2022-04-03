# GO: Hello World in Docker using a multi-stage build
This Go hello world app is compiled and build inside a docker container and at the end we create a docker image based in alpine to run the app. The final image has 7.23MB.
## How to run using docker

```
docker run --rm julianocanuto/go-app-multi-stage-build:v1
```