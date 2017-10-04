# Docker image for ElasticMQ

Docker image for [ElasticMQ](https://github.com/adamw/elasticmq) (fake SQS)

Run it with
```
docker run -p 9324:9324 bangpound/elasticmq
```

Custom config `elasticmq.conf` can be mounted to `/etc/elasticmq/`:
```
docker run -p 9324:9324 -v "$PWD:/etc/elasticmq" bangpound/elasticmq
```
