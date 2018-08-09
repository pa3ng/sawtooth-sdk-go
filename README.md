# sawtooth-sdk-go

This fork builds a variant Docker image with golang 1.10 installed and with the sawtooth-sdk-go project premounted.

## Getting Started

Build the Go SDK image

```
docker build . -t sawtooth-sdk-go
docker run sawtooth-sdk-go
```

This will build the protos / mocks and place them in the protobuf / mocks directory, respectively.
