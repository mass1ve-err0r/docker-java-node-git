FROM timbru31/java-node:8-alpine@sha256:07bd85f3ae2d91bf572e61ee9908ab2ac98859ff2d259281cc04ebf33612940a
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
