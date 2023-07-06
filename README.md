# 👨‍💻 Docker tutorial

## 1. Build your Docker image by running the following command in the project directory:

```shell
docker build -t <username>/<repository> .
```

## 2. Login to Docker Hub by running the following command and entering your Docker Hub credentials when prompted:


```shell
docker login
```

## 3. Once you are logged in, push the Docker image to Docker Hub using the following command:

```shell
docker push <username>/<repository>
```

## 4. After the push is complete, you can verify that your image is available on Docker Hub by visiting the following URL in your web browser:

```shell
https://hub.docker.com/r/<username>/<repository>
```