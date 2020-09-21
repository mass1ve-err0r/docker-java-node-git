FROM timbru31/java-node:8-alpine@sha256:89a3c11d6ddc2cb3379f45c11362a7a1383e779bb432dc13d138b41d45bf59c5
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
