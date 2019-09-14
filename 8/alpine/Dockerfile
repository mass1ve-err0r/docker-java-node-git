FROM timbru31/java-node:8-alpine@sha256:7d883c824061641f3928bbeffd8cc0ec099190f8a154137ca7136d0c20d08ac2
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git=2.23.0-r1
