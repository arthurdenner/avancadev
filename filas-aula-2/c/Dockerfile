FROM golang:1.15

WORKDIR /go/src/c

COPY . .

RUN GOOS=linux go build -o c
RUN ls -la
EXPOSE 9092

ENTRYPOINT [ "./c" ]