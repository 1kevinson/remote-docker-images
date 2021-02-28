FROM ubuntu

LABEL author="Arsene Kevin" \
      description="Docker image for DBeaver" \
      version="1.0"

WORKDIR /app

RUN add-apt-repository ppa:serge-rider/dbeaver-ce && \
    apt-get update && \
    apt-get install dbeaver-ce

