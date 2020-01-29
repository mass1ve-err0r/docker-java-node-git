FROM timbru31/java-node:11-alpine@sha256:f42bddbc1c3be5605c27d0e3d7c507a59418d448b553d5ae4a99c2113ab0d417
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
