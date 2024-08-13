# gotest2sql

inserts the output of go test -json ./... into a sqlite database

## Usage

```
go test -json ./... | go run github.com/marcopolo/gotest2sql -output ./test_results.db
```
