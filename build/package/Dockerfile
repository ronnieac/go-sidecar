FROM alpine:latest
RUN apk --no-cache add ca-certificates
WORKDIR /workspace/
COPY go-sidecar .
CMD ["./go-sidecar"]