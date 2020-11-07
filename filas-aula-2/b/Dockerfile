FROM golang:1.15

WORKDIR /go/src/b

COPY . .

RUN GOOS=linux go build -o b
RUN ls -la

ENTRYPOINT [ "./b" ]