# go-micro-product

Split from monorepo go-micro (product-service/). Original go-micro folder is left untouched.

## Build

```bash
go test ./...
docker build -t minhtri1612/product-service:dev .
```

## CI

Thin Jenkinsfile -> Shared Library go-micro-ci (repo go-micro-pipeline-lib).