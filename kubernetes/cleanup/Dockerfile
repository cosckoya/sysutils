FROM alpine:latest

RUN apk add bash curl docker --no-cache \
 && rm -rf /var/cache/apk/*

# Install Kubectl
ARG KUBECTL_VERSION=v1.17.3
RUN wget -q https://storage.googleapis.com/kubernetes-release/release/${KUBECTL_VERSION}/bin/linux/amd64/kubectl \
    --directory-prefix=/usr/local/bin/
