FROM python:2
LABEL name python2-test-env
LABEL maintainer "Matt Bacchi"

RUN pip install cryptography ipython mock pycodestyle requests responses
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - && apt-get install -y nodejs

CMD bash
