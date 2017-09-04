FROM ubuntu:16.04
MAINTAINER Katsunori Kanda <potix2@gmail.com>

RUN apt-get update && \
    apt-get install -y bats && \
    rm -rf /var/lib/apt/lists/*
ENTRYPOINT ["/usr/bin/bats"]
CMD ["-v"]
