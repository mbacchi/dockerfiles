FROM python:3
LABEL name python3-test-env
LABEL maintainer "Matt Bacchi"

RUN pip install cryptography ipython mock pycodestyle requests
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - && apt-get install -y nodejs

CMD bash
