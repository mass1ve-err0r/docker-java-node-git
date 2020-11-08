FROM timbru31/java-node:8-alpine@sha256:7912f715a6e056170f7c39dcf1553c4e14172fec42c3b1e24d04fd6dcb8ca129
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
