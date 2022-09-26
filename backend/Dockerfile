FROM golang:1.19

WORKDIR /go/src/github.com/ryoshindo/trivy-api/backend

COPY go.mod go.sum ./

RUN go install \
    github.com/cosmtrek/air
