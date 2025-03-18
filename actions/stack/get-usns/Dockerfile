FROM golang:alpine:1.24

COPY entrypoint /tmp/entrypoint
RUN cd /tmp/entrypoint && go build -o /entrypoint .

ENTRYPOINT ["/entrypoint"]

