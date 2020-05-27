# mongo-cluster-docker

This is a simple 3 node replica mongodb setup based on official `mongo` docker image.

# Run

```
docker-compose -f docker-compose.1.yml -f docker-compose.2.yml up -d
docker-compose -f docker-compose.cnf.yml up -d
docker-compose -f docker-compose.shard.yml up -d
```

