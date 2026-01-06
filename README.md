## location-tracker-kafka
Simple streaming application that tracks the latest location of simulated drivers

#### Pre-requisites
- Python 3.x
- Docker and Docker Compose


#### Skills needed
- Kafka Streaming

#### Start the Kafka broker and ksqlDB Server in the background
```
docker-compose up -d
```

#### Start the ksqlDB CLI to submit SQL statements to the ksqlDB Server
```
docker exec -it ksqldb-cli ksql http://ksqldb-server:8088
```
