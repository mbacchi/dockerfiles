# Python 3

I was unable to use the official Python Docker images for Debian buster on my x86-64 based system. It appears that the only available images for x86-64 are alpine linux. This was uncovered with the following command:

```
$ DOCKER_CLI_EXPERIMENTAL=enabled docker manifest inspect -v python:3.7-buster | jq '.[0].Descriptor.platform'
{
  "architecture": "arm",
  "os": "linux",
  "variant": "v5"
}
```

So I had to use the official Python Docker image for alpine:

```
$ DOCKER_CLI_EXPERIMENTAL=enabled docker manifest inspect -v python:3.7-alpine | jq '.[0].Descriptor.platform'
{
  "architecture": "amd64",
  "os": "linux"
}
```
