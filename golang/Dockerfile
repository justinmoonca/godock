FROM golang:1.20.3-alpine

LABEL maintainer="Justin <justinmoonca@gmail.com>"

# install requirement packages
RUN apk update --no-cache && apk add --no-cache tzdata

# $GOPATH/bin => $PATH
ENV PATH $GOPATH/bin:$PATH

WORKDIR /usr/src/code

EXPOSE 8000
EXPOSE 8001
EXPOSE 8002
EXPOSE 8003
EXPOSE 9000
EXPOSE 9001
EXPOSE 9002
EXPOSE 9003