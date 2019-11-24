FROM golang:latest
LABEL maintainer="mc222ap@student.lnu.se"

WORKDIR /app

RUN go mod download

COPY . .

RUN go build -o main

EXPOSE 8080

CMD ["./main"]

