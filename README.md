# Bazel C++ websocket example

The ws uses boost rules which is outline [here](https://github.com/nelhage/rules_boost/tree/master). 

To start the server:
```bash
bazel run //test:websocket_server_async
```

To send a request:
```bash
bazel run //test:websocket_client_async
```
