FROM debian

MAINTAINER amazhara

RUN apt-get update && apt-get install -y cowsay fortune

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay

# docker build -t ex01 . && docker run --rm -t ex01
