FROM timbru31/java-node:11-alpine@sha256:3adfb2a2edb7e0ed3061a844200e4ad29282ac7f2be59756dc68f3de26de8679
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
