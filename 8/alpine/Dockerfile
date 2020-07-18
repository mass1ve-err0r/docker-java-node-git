FROM timbru31/java-node:8-alpine@sha256:c28c73f6d741e80a6ee20a25aed720e343f3c796ecb93311565c27d44e7e0089
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
