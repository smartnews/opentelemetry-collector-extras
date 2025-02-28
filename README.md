# OpenTelemetry Collector Extras

See the [Developing guide](DEVELOPING.md) to get started with building and running the OpenTelemetry Collector with the extras in
this repository.

## Processors
- [metricsasattributesprocessor](metricsasattributesprocessor/README.md)

## Build and push
Use docker buildx to build and push the docker image.

```bash
docker buildx build --platform linux/amd64,linux/arm64 --push -t 165463520094.dkr.ecr.ap-northeast-1.amazonaws.com/ops-reliability/otel-collector:<tag> .
```
