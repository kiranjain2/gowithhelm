FROM golang:1.11 as builder
WORKDIR $GOPATH/src
COPY gotrial.go .
RUN go build gotrial.go
EXPOSE 8000
CMD ["./gotrial"]
