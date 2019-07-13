FROM python:3.7-alpine
LABEL name python37-test-env
LABEL maintainer "Matt Bacchi"

RUN apk add build-base libffi-dev openssl-dev python3-dev nodejs && pip install cryptography ipython mock pycodestyle requests

CMD bash
