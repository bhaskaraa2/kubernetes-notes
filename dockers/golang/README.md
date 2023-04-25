

```bash
go run main.go
```



```bash
docker build . -t golang-build
```


Test Docker 

```bash
docker run --name test-golang-container -p 8090:8090 -d golang-build
```
