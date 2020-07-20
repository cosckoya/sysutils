FROM alpine:3.9

COPY ./scripts/clean-docker.sh ./scripts/clean-kubernetes.sh /bin/
RUN chmod 755 /bin/clean-docker.sh /bin/clean-kubernetes.sh

RUN apk add bash curl docker --no-cache \
    && rm -rf /var/cache/apk/*

ENV KUBE_VERSION v1.9.3
RUN cd /usr/local/bin \
    && curl -O https://storage.googleapis.com/kubernetes-release/release/${KUBE_VERSION}/bin/linux/amd64/kubectl \
    && chmod 755 /usr/local/bin/kubectl
