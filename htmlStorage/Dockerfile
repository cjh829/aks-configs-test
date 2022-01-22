#store new htmls in docker image
FROM alpine:latest
RUN apk add --no-cache rsync
RUN mkdir /newData
ADD htmldata /newData
RUN chmod +r /newData
