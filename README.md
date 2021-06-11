# Simple Playground for Kafka

## Setup

using docker compose

```bash
docker-compose up -d
```

once ready (it takes a while) you should be able tio visit
http://localhost:9021 to view the kafka cluster

## Publisher

simple publisher example copied from the go sdk

```bash
go run cmd/publisher/main.go
```

## Consumer

simple consumer example copied from the go sdk

```bash
go run cmd/consumer/main.go
```

## Resources

* [Confluent kafka docker quickstart][1]
* [Confluent Kafka Go SDK][2]

[1]: https://docs.confluent.io/platform/current/quickstart/ce-docker-quickstart.html#ce-docker-quickstart
[2]: https://github.com/confluentinc/confluent-kafka-go


