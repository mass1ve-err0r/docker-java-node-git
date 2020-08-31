FROM timbru31/java-node:11-alpine@sha256:c3d366ef8fa38d88c4068c2bc4af213b4ee1516d2986ff29e6986c6eb6039f37
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
