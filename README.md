# daprstatestore

based on https://github.com/boj/redistore/tree/master

```bash
#iniciar dapr sidecar local sin la app nodejs. Esto deja ocupada la terminal, debe inicar otra terminal para ejecutar otros comandos
dapr run --log-level debug --app-id daprstatestore-test --dapr-http-port 47777 --dapr-grpc-port 63337 --resources-path "./components4test"
```
