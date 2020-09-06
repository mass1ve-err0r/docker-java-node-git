FROM timbru31/java-node:8-alpine@sha256:c25bc5daaedb46728aa11d6a232ca84e8b500125ac0a2f27a91e67bf36fef6c7
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
