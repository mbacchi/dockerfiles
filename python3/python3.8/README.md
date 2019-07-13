# Docker image for Python3.8

A simple image built on Alpine for Python 3.8.

## Build image
```
$ docker build . -t python3.8
Sending build context to Docker daemon  2.048kB
Step 1/5 : FROM python:3.8-rc-alpine
3.8-rc-alpine: Pulling from library/python
050382585609: Already exists 
```

## Run container

```
$ docker run -i -t python3.8 /bin/sh
/ # python --version
Python 3.8.0b2
/ # 
```