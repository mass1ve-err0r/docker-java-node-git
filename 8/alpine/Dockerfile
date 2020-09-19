FROM timbru31/java-node:8-alpine@sha256:3462d143d42709ab84f9ece7d345132ba534e724f99748fbd9cece8d20d3b557
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
