FROM timbru31/java-node:8-alpine@sha256:f296e923fc88edda7021ea573d4c53aa8728c8ba6037e05d190ec10600c72fa6
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
