FROM timbru31/java-node:8-alpine@sha256:9bb1288adefea637d43ed563ae06e73ad1f4a24c83b8ece13571b2edeb4eb19d
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
