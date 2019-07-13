# Docker image for Python3.5

A simple image built on Alpine for Python 3.5.

## Build image
```
$ docker build . -t python3.5
Sending build context to Docker daemon  2.048kB
Step 1/6 : FROM python:3.5-alpine
 ---> 863cb8b335b6
```

## Run container

```
$ docker run -i -t python3.5 /bin/sh
/ # python --version
Python 3.5.7
/ # 
```