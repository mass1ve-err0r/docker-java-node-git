FROM timbru31/java-node:8-alpine@sha256:eecda843212cdbb9a5f2353da589944192c8125697e8384b8fa9fca59483be29
LABEL maintainer "Nathan Friend <hello@nathanfriend.io>"

ARG REFRESHED_AT
ENV REFRESHED_AT $REFRESHED_AT

RUN apk add --repository http://dl-cdn.alpinelinux.org/alpine/edge/main/ --no-cache git
