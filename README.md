# KONG db-less  example
- start
```
docker-compose up -d
```
- update config using [`HTTPIe`](https://httpie.io/)
```
http :8001/config config=@kong.yaml
```