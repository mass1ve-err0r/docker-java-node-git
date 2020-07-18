FROM timbru31/java-node:11-alpine@sha256:9562b8dc273543a0b994c5d3315633e445db28cd62d3ef5f22f78c958dce970d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
