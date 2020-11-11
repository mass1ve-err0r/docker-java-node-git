FROM timbru31/java-node:11-alpine@sha256:917fbb41a21aae1ec2226345b55ed500de8c65c4991688e7adffc0311ac4146c
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
