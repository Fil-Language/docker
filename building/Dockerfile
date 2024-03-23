# syntax=docker/dockerfile:1
FROM alpine:latest
RUN apk update && \
    apk upgrade && \
    apk add git cmake make g++ openjdk17-jre llvm15-dev llvm15-static;
