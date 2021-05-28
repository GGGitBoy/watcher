FROM alpine:3
RUN apk update
RUN apk add curl
COPY watcher /watcher
CMD ["/watcher"]