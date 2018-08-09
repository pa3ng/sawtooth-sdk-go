# sawtooth-sdk-go

This fork builds a variant Docker image with golang 1.10 installed, the sawtooth-sdk-go project premounted, and the sdk protos prebuilt.

This image is publically available at [pa3ng/sawtooth-sdk-go](https://hub.docker.com/r/pa3ng/sawtooth-sdk-go/). To obtain this image, do:

```
> docker pull pa3ng/sawtooth-sdk-go
```

## Build image from project

Build the Go SDK image locally

```
> git clone https://github.com/pa3ng/sawtooth-sdk-go.git
> cd sawtooth-sdk-go
> docker build . -t sawtooth-sdk-go
> docker run sawtooth-sdk-go
```

This will build the protos / mocks and place them in the protobuf / mocks directory, respectively.
