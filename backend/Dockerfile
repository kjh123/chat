FROM golang:latest

ENV GOPROXY https://goproxy.cn,directory
RUN mkdir /app
ADD . /app/
WORKDIR /app
RUN go mod download
RUN go build -o chat ./...

EXPOSE 8080
CMD ["/app/chat"]
