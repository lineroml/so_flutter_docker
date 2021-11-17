# Flutter Dashboard in Docker

## Getting Started with Flutter

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## Run with [Docker Playground](https://labs.play-with-docker.com)

1. Execute following code in a new instance (Click in "New Instance") in Docker Playground:
```
docker pull 200125556/flutter_dashboard:final
docker run -i -p 8080:5000 -td 200125556/flutter_dashboard:final
```
Note: You can paste with ctrl + shift + v 

2. Click on port 8080 and enjoy!


## How to run in docker

Open cmd (ctrl + r, type cmd, enter). <br>

### Run the following commands in order (after cloning repo):

```
docker build . -t flutter_dashboard
```
```
docker run -i -p 8080:5000 -td flutter_dashboard
```
### Open in your browser [localhost](http://localhost:8080/)

## bibliography

1. [Flutter Dashboard Demo](https://morioh.com/p/fd4bce4016b8)
2. [Containerizing Flutter web apps with Docker](https://blog.logrocket.com/containerizing-flutter-web-apps-with-docker/)
3. [DockerHub Repositories Documentation](https://docs.docker.com/docker-hub/repos/)

## Made by

1. Arnaldo Benavides
2. Luisa Escobar

## Link to DockerHub repo

- [flutter-dashboard repo](https://hub.docker.com/repository/docker/200125556/flutter_dashboard)
