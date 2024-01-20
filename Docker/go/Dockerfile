FROM golang:1.21

WORKDIR /usr/src/app

RUN go mod init github.com/Alex-Ferreira-Santos/devops-studies
RUN echo "package main;import \"fmt\"; func main(){fmt.Print(\"hello world\")}" >> dockergo.go
RUN go build -o bin/dockergo

ENTRYPOINT [ "./bin/dockergo" ]