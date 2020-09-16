FROM timbru31/java-node:8-alpine@sha256:09296593315d8d92ccaadad500a941241c824b0cd778bb47598beda10a551410
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
