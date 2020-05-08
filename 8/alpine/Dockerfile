FROM timbru31/java-node:8-alpine@sha256:85061a23bf3831a02e7dfdd2f854c4e6308837ca06d722beeb0520941be7049f
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
