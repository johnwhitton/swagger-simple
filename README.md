# swagger-simple
Simple Swagger Server

## Notes on building

http://54.201.207.240:8082/docs

```
swagger generate server -A todo-list -f ./swagger.yml
go install ./cmd/todo-list-server/
todo-list-server --port=8765
swagger serve swagger.yml --port 8082 --host=0.0.0.0 --no-open
```
