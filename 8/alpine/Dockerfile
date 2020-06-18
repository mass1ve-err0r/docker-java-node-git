FROM timbru31/java-node:8-alpine@sha256:507bf1d7e41e58ea669cd7f90482521d3a1f64bb82b4cb05bf84f5a73a7fe148
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
