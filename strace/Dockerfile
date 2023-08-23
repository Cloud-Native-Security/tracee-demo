FROM alpine:3.18.3
RUN apk update && apk add strace
CMD exec /bin/sh -c "strace ls && trap : TERM INT; sleep 9999999999d & wait" 