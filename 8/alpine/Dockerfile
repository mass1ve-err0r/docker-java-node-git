FROM timbru31/java-node:8-alpine@sha256:2993039dbccc28cd4bd9194ad38911390c7fde2966234b121eb96519a31d7dcd
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
