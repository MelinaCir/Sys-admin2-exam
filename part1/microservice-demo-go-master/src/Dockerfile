FROM golang:latest
LABEL maintainer="mc222ap@student.lnu.se"

RUN mkdir /app 

ADD . /app/ 

WORKDIR /app 

RUN go get github.com/gorilla/mux

RUN go build -o main . 

EXPOSE 8080

CMD ["/app/main"]