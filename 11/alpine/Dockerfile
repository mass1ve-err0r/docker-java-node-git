FROM timbru31/java-node:11-alpine@sha256:b80104aa222a258e4c68c2ccf1c26442efea8bc9f5412bf321bc519a92c9addb
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
