FROM golang:alpine3.15 AS builder

WORKDIR /var/www/app

COPY ./main.go /var/www/app/

RUN go mod init fullcycle.com
RUN go build -o build/fullcycle


FROM scratch

WORKDIR /var/www/app
COPY --from=builder /var/www/app/build /var/www/app

ENTRYPOINT ["./fullcycle"]


