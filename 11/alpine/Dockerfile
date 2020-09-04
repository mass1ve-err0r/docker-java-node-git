FROM timbru31/java-node:11-alpine@sha256:a2730ee9a301e5956b436e740138117dfd6d57a79e4ef959d40d70666b1e83f4
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
