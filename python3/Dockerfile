FROM python:3-alpine
LABEL name python3-test-env
LABEL maintainer "Matt Bacchi"

RUN apk add build-base libffi-dev openssl-dev python3-dev nodejs && pip install cryptography ipython mock pycodestyle requests

CMD bash
