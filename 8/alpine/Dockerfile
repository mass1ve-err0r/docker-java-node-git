FROM timbru31/java-node:8-alpine@sha256:121df6a082d6d11f4bcea7a7a17bbf68e1fe762acee7c38031419e784d6b90e5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
