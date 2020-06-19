FROM timbru31/java-node:8-alpine@sha256:2ab1dc51748a2fc2ef411abccc3492d8c12031cdd8422ecedd4ad5557c887f62
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
