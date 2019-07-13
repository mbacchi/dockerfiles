# Docker image for Python3.6

A simple image built on Alpine for Python 3.6.

## Build image
```
$ docker build . -t python3.6
Sending build context to Docker daemon  3.072kB
Step 1/5 : FROM python:3.6-alpine
3.6-alpine: Pulling from library/python
050382585609: Already exists 
dac2222ca532: Already exists 
43ac3d7b49f5: Pull complete 
```

## Run container

```
$ docker run -i -t python3.6 /bin/sh
/ # python --version
Python 3.6.9
/ # 
```