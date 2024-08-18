# kafka-basics


Consume Messages from a Topic
```
docker exec -it -u root kafka /bin/sh
find / -name kafka-console-consumer
```

```
/usr/bin/kafka-console-consumer --bootstrap-server localhost:9092 --topic basics --from-beginning
```