# Docker Kafka Zookeeper

## Version
```
Kafka: 2.5.0
Zookeeper: 3.6.1 
```

## Run
* Start container
```sh
$ docker-compose up
```
  
* Stop container
```sh
$ docker-compose down
```

## Port Forwarding
|Host|Container|Service|
|:---:|:---:|:---:|
|9092|9092|Kafka|
|2181|2181|Zookeeper|
