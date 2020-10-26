FROM timbru31/java-node:8-alpine@sha256:730b34a08a35ab582deba4f5fadc101253d402b349b9303656fb1c0eaa519027
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
