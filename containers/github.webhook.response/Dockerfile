FROM golang:1.13.5-alpine3.11
RUN mkdir /dist
WORKDIR /root/app
CMD go build && mv app /dist && /dist/app