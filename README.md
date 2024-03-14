# kafka-workshop
## Comands used:
``
docker-compose up -d
``
### Verify that both the servers are listening on the respective ports

```
nc -zv localhost 22181
```

```
nc -zv localhost 29092
```
### Check the verbose logs while the containers are starting up and verify that the Kafka server is up:

```
docker-compose logs kafka | grep -i started
```
