#Container V 1.0

FROM golang:alpine

RUN mkdir /files
COPY helloWorld.go /files
WORKDIR /files

RUN go build -o /files/helloWorld helloWorld.go
ENTRYPOINT ["/files/helloWorld"]
