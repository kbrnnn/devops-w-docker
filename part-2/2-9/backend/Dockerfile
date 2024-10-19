FROM golang:1.16-alpine

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

# ENV REQUEST_ORIGIN=http://frontend:5001/

RUN go build

CMD ["./server"]