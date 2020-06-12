FROM timbru31/java-node:11-alpine@sha256:e9d02e5096f09f6185d6a4b36fb340e006a9db7b14ddf8225b2cd41ddb4fe94b
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
