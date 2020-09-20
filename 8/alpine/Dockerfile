FROM timbru31/java-node:8-alpine@sha256:b86184759d492dcfd4ad942e6b28c566b33631051ebb4f7793f60735bae72037
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
