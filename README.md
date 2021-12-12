# Govee Collector proto

Protocol Buffer files of [govee_collector](https://github.com/Samarkin/govee_collector).

## What?

Files in this repository describe the [gRPC](https://grpc.io) interface of `govee_collector`.

## How to use?

1. Include this repository as a submodule in the service that needs to access data from `govee_collector`:

   ```shell
   git submodule add https://github.com/Samarkin/govee_collector_proto
   ```

2. Follow instructions specific to your programming language:

   https://grpc.io/docs/languages/

## Why?

Separate repository simplifies code sharing between projects,
especially if they are written in different languages.
