FROM timbru31/java-node:11-alpine@sha256:554ca17d055af77b961d6219e92fe417984e4385bd7f1d0969c3774bfa5501fa
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
