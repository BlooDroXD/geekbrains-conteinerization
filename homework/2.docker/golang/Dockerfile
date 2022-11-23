FROM golang:1.18-alpine

WORKDIR /golang_app

COPY . ./

RUN 	go mod download && \
	go build -o ./app
	

EXPOSE 8080

ENTRYPOINT ./app


