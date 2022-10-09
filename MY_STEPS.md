# manual steps

## install redis

no installation needed, below command starts a redis server:

```
docker run --name some-redis -p 6379:6379 -d redis redis-server --save 60 1 --loglevel warning
```
(if name clashes, remove --name param)

below command starts the cli tool 

```
redis-cli
```
you can ping afterwards

---

## app insights

* first deployment with "dependency map" for vmss failed
* app insights instrumentation key : `b14c8720-3ccb-443d-8bb5-5fbd150da992`
